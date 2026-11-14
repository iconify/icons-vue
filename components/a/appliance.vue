<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ops4c2bme"/><path class="txi-p40ne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:appliance" /></template>
<style>
.ops4c2bme {
  d: path("M3 3h18v18H3Zm0 5h18M7 5.5h.01m3.49 0h.01");
}

.txi-p40ne {
  d: path("M7 11.5h10v6H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
