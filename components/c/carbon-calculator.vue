<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vk16nljwz"/><path class="aaazjgeka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-calculator" /></template>
<style>
.aaazjgeka {
  d: path("M6 5.5h7v3H6ZM6 12h.01m3.49 0h.01M13 12h.01M6 15h.01m3.49 0h.01M6 18h.01m3.49 0h.01m5.74 3H20a1.75 1.75 0 0 0 0-3.5a2.75 2.75 0 0 0-5.25.25a1.75 1.75 0 0 0 .5 3.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vk16nljwz {
  d: path("M11.6 21.5H3v-19h13V13");
}

</style>
