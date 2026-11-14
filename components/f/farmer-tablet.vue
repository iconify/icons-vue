<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="btqpfca9b"/><path class="s1air6t3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farmer-tablet" /></template>
<style>
.btqpfca9b {
  d: path("M4.5 2.5h15v19h-15Zm6 16h3m-1.5-3v-5");
}

.s1air6t3e {
  d: path("M12 10.5c0-2.5-1.5-4-4.25-4c0 2.5 1.75 4 4.25 4Zm0 0c0-2.5 1.5-4 4.25-4c0 2.5-1.75 4-4.25 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
