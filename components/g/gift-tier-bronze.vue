<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ls6r6kb_p"/><path class="kaeh4oboj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-tier-bronze" /></template>
<style>
.kaeh4oboj {
  d: path("M5 7.75v2a7 3 0 0 0 14 0v-2M2.5 19.5h19M5 19.5v-4h14v4");
}

.ls6r6kb_p {
  d: path("M5 7.75a7 3 0 1 0 14 0a7 3 0 1 0-14 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
