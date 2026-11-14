<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lcmgkac4b"/><path class="fgypfbc5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:frame-hanging-wire" /></template>
<style>
.fgypfbc5b {
  d: path("m6 18l3.5-3.5l3 2.25L15 14.5l3 3");
}

.lcmgkac4b {
  d: path("M2.5 10h19v11h-19Zm6 0L12 4.5l3.5 5.5M12 2.5v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
