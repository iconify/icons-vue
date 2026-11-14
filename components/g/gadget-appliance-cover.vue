<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u8zhxxbbm"/><path class="xp4fghtnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gadget-appliance-cover" /></template>
<style>
.u8zhxxbbm {
  d: path("M3.5 2.5h17v19h-17Zm0 5h17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xp4fghtnw {
  d: path("M7.75 14.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0ZM7 5h.01");
}

</style>
