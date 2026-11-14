<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cy4-77bft"/><path class="lmjup-bem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:adventure-race" /></template>
<style>
.cy4-77bft {
  d: path("M13.608 18.822L8.5 16.5l-6 2.5V5l6-2.5L14 5l6.5-2.5v10.694M8.5 2.5v14M14 5v5.3M5.5 13h.01m5.74-3.5h.01");
}

.lmjup-bem {
  d: path("M16.5 21.5v-7l4.5 2l-4.5 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
