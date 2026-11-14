<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e3ov5ebhy"/><path class="yevg0v86k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gas-bill" /></template>
<style>
.e3ov5ebhy {
  d: path("M4.5 2.5h15v19L17 20l-2.5 1.5L12 20l-2.5 1.5L7 20l-2.5 1.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yevg0v86k {
  d: path("M12 5.5c1 3 4 4 4 8a4 4 0 0 1-8 0c0-2 1-3 2-4c0 1.5.75 2.25 1.5 2.5c0-2.5-.5-4.5.5-6.5Z");
}

</style>
