<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fl9_mqtqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:badminton-doubles" /></template>
<style>
.fl9_mqtqu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM2.5 21.5c0-3.25 1.75-5 4-5s4 1.75 4 5M14.75 11a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM13.5 21.5c0-3.25 1.75-5 4-5s4 1.75 4 5M9 2.5h6L13.5 7h-3ZM10.5 7a1.5 1.5 0 0 0 3 0");
}

</style>
