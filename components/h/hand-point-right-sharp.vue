<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="gc9lubb2q"/><path class="pzeu8sbvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-point-right-sharp" /></template>
<style>
.gc9lubb2q {
  d: path("M12 7h9.25v2.5H14a1.25 1.25 0 0 1 0 2.5a1.25 1.25 0 0 1 0 2.5a1.25 1.25 0 0 1 0 2.5H8.5c-3 0-5.25-2-5.25-5V7h4Z");
}

.pzeu8sbvb {
  d: path("m6.25 11l2.65-.757l2.35 1.007");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
