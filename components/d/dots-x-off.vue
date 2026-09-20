<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="zm0the13b"/><circle class="ehbqml5ic"/><circle class="z4qfeoj9o"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:dots-x-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ehbqml5ic {
  cx: 10px;
  cy: 10px;
  r: 2px;
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.z4qfeoj9o {
  cx: 15px;
  cy: 10px;
  r: 2px;
}

.zm0the13b {
  cx: 5px;
  cy: 10px;
  r: 2px;
}

</style>
