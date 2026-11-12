<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rcb131b7v"/><path class="yithp4hrr"/><path class="w312zsb4r"/><path class="p5gw4-bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:kanban-square-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p5gw4-bye {
  d: path("M12 6L12 11");
}

.rcb131b7v {
  d: path("M12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46446C4.92893 2 7.28596 2 12 2Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w312zsb4r {
  d: path("M17 6L17 18");
}

.yithp4hrr {
  d: path("M7 6L7 15");
}

</style>
