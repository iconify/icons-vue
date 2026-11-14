<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="adwots7km"/><path class="g0bpo06pp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gearbox" /></template>
<style>
.adwots7km {
  d: path("m10.75 11.75l.25 1.5l-1.25.5L9 12.5H7.5l-.75 1.25l-1.25-.5l.25-1.5l-1-1l-1.5.25l-.5-1.25L4 9V7.5l-1.25-.75l.5-1.25l1.5.25l1-1l-.25-1.5l1.25-.5L7.5 4H9l.75-1.25l1.25.5l-.25 1.5l1 1l1.5-.25l.5 1.25l-1.25.75V9l1.25.75l-.5 1.25l-1.5-.25Zm4.5 2.5V13l1.25-.5l.75 1.25l1.25.25l1.25-.75l1 1L20 15.5l.25 1.25l1.25.75l-.5 1.25h-1.25l-1 1V21l-1.25.5l-.75-1.25L15.5 20l-1.25.75l-1-1L14 18.5l-.25-1.25l-1.25-.75l.5-1.25h1.25Z");
}

.g0bpo06pp {
  d: path("M6.75 8.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM17 17h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
