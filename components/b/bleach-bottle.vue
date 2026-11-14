<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jdm4rmbnk"/><path class="cms81rbfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bleach-bottle" /></template>
<style>
.cms81rbfl {
  d: path("M12 11c1.5 1.75 2.75 3.5 2.75 5a2.75 2.75 0 0 1-5.5 0c0-1.5 1.25-3.25 2.75-5Z");
}

.jdm4rmbnk {
  d: path("M5 21.5V10l3-2.5h10A1.5 1.5 0 0 1 19.5 9v11a1.5 1.5 0 0 1-1.5 1.5Zm2-18h4v4H7Zm7 4v-3h3.5A1.5 1.5 0 0 1 19 6v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
