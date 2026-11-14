<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ngie_sbgu"/><path class="vpyrvp8lb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:assume-role" /></template>
<style>
.ngie_sbgu {
  d: path("M4 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM2.5 21c0-3 1.75-5 4-5s4 2 4 5M15 10.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM13.5 21c0-3 1.75-5 4-5s4 2 4 5M7 5c2-2.5 8-2.5 10 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vpyrvp8lb {
  d: path("M14.25 5H17V2.25");
}

</style>
