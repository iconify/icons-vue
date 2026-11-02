<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v3kusnb_o"/><path class="a2f-6zbpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-sync-corner-duotone" /></template>
<style>
.a2f-6zbpz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19A5 5 0 0 1 7 9c1.819-6.366 9.638-6.116 11 0m1 4a4.472 4.472 0 0 1 0 8m3 0h-3v-3m-4 3a4.472 4.472 0 0 1 0-8m-3 0h3v3");
}

.ft5dv1b6b {
  fill: none;
}

.v3kusnb_o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 10a.997.997 0 0 0-1 1v8a1 1 0 0 1-1 1H7a6 6 0 0 1-.739-11.956c.754-2.033 2.254-3.712 4.346-4.404c2.878-.951 5.911.244 7.461 2.828c.426.718.732 1.499.908 2.315A1 1 0 0 1 18 10Z");
}

</style>
