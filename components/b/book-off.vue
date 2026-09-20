<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="u8n-f4bsl"/><path clip-rule="evenodd" class="p733ncasu"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:book-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p733ncasu {
  fill-rule: evenodd;
  d: path("M20 5a2 2 0 0 0-2.323-1.974L9.838 4.31A1 1 0 0 0 9 5.297V17a1 1 0 0 0 1.155.988l8.154-1.276A2 2 0 0 0 20 14.737zm-2 9.737l-7 1.094V6.147L18 5z");
}

.u8n-f4bsl {
  fill-rule: evenodd;
  d: path("M11 5.297a1 1 0 0 0-.838-.987L2.323 3.026A2 2 0 0 0 0 5v9.737a2 2 0 0 0 1.69 1.975l8.155 1.276A1 1 0 0 0 11 17zm-9 9.44V5l7 1.147v9.684z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
