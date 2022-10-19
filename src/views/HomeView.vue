<template>
  <TreeView />
</template>

<script>
import { defineComponent } from "vue";

// Components
import HelloWorld from "../components/HelloWorld.vue";
import TreeView from "../components/TreeView.vue";

export default defineComponent({
  // name: "HomeView",
  name: "TreeView",

  components: {
    // HelloWorld,
    TreeView,
  },
});
</script>
