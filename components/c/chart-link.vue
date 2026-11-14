<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qr98uh62i"/><path class="vd-aezllp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-link" /></template>
<style>
.qr98uh62i {
  d: path("M3.5 3v17.5h8.8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vd-aezllp {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m-3.25 13.25l-.25.25a1.75 1.75 0 0 0 2.5 2.5l.25-.25m-.5-4.5l.25-.25a1.75 1.75 0 0 1 2.5 2.5l-.25.25M17 19l2-2");
}

</style>
