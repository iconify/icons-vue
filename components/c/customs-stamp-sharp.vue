<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pava-dbkv"/><path class="etm8-mbct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:customs-stamp-sharp" /></template>
<style>
.etm8-mbct {
  d: path("m10 17l1.5 1.5l3-3m2.15-12.43l.94.34l.47.17l-.17.47l-.52 1.41l-.17.47l.47.17l.94.35l.47.17l-.17.47l-.51 1.41l-.17.47l-.47-.17l-4.7-1.72l-.47-.17l.17-.47l.51-1.41l.17-.47l.47.17l.94.35l.47.17l.17-.47l.52-1.41l.17-.47z");
}

.pava-dbkv {
  d: path("M4.75 12.25h14.5v9H4.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
