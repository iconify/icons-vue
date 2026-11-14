<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hmhi_sn9z"/><path class="cxyl9s35b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biathlete" /></template>
<style>
.cxyl9s35b {
  d: path("M2.5 20.5h17q2 0 2-2M5 12.5l6-6");
}

.hmhi_sn9z {
  d: path("M13.75 5.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm.25 4.5L9.5 14m0 0l3.5 3l-1 3.5M9.5 14L7 20.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
