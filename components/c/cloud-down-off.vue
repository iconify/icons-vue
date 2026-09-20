<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jhwoxibja"/><path class="gt8trh0gk"/><path class="il75aeb3t"/><path class="quvmab-hr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cloud-down-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gt8trh0gk {
  d: path("M9.5 10a1 1 0 1 1 2 0v7.5a1 1 0 1 1-2 0z");
}

.il75aeb3t {
  d: path("M12.375 14.72a1 1 0 1 1 1.25 1.56l-2.5 2a1 1 0 0 1-1.25-1.56z");
}

.jhwoxibja {
  fill-rule: evenodd;
  d: path("M11 3h-1a4 4 0 0 0-3.874 3H6a4 4 0 1 0 0 8h8a4 4 0 0 0 .899-7.899A4 4 0 0 0 11 3M7.676 8l.387-1.501A2 2 0 0 1 10 5h1c.937 0 1.743.65 1.95 1.549l.28 1.221l1.221.28A2.002 2.002 0 0 1 14 12H6a2 2 0 1 1 0-4z");
}

.quvmab-hr {
  d: path("M7.375 16.28a1 1 0 1 1 1.25-1.56l2.5 2a1 1 0 0 1-1.25 1.56zM1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
