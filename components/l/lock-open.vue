<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="dowozdblg"/><path class="azt7m7kqg"/><path clip-rule="evenodd" class="muiqxrbuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:lock-open" /></template>
<style>
.azt7m7kqg {
  d: path("M8 8a1 1 0 1 1-2 0V4a4 4 0 1 1 8 0v.5a1 1 0 1 1-2 0V4a2 2 0 1 0-4 0z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dowozdblg {
  fill-rule: evenodd;
  d: path("M13 7H7a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4v-4a4 4 0 0 0-4-4m-8 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2z");
}

.muiqxrbuk {
  fill-rule: evenodd;
  d: path("M8 13a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2.5 0a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

</style>
