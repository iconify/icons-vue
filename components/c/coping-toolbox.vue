<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pu5r6cscu"/><path class="p2rpd_bqi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coping-toolbox" /></template>
<style>
.p2rpd_bqi {
  d: path("m12.075 2.398l4.698 1.711l-1.026 2.819l-4.698-1.71ZM10.25 11.5h3.5v3h-3.5Z");
}

.pu5r6cscu {
  d: path("M3 11.5h18V21H3Zm1.941-8.506l16.914 6.157L21 11.5L4.086 5.344Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
