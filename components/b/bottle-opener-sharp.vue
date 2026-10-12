<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="he8y57bec"/><path class="yuxmrvcgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bottle-opener-sharp" /></template>
<style>
.he8y57bec {
  d: path("M10 12.33v8.92h4v-8.92a5 5 0 1 0-4 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yuxmrvcgk {
  d: path("M9.5 6.5h5a2.5 2.5 0 0 1-5 0Z");
}

</style>
