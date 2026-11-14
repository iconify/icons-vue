<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fecvl39au"/><path class="p-hv4gbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:league-signup" /></template>
<style>
.fecvl39au {
  d: path("M14.3 21.5H3.5V4h14v11.3");
}

.p-hv4gbht {
  d: path("M7.5 2.5h6v3h-6ZM7 10h7m.75 8l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
