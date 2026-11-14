<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hqdilwbrj"/><path class="o2dukb49a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anatomy-torso" /></template>
<style>
.hqdilwbrj {
  d: path("M9 3C7 4.5 3.5 4.5 3 7.5l2.5 14h13l2.5-14c-.5-3-4-3-6-4.5");
}

.o2dukb49a {
  d: path("M12 2.5V7l-1.75 1.5M12 7l1.75 1.5m-3.5 0V17H8c-1 0-1.25-1-1-2l.75-4.5c.25-1.25 1.25-2 2.5-2Zm3.5 0V17H16c1 0 1.25-1 1-2l-.75-4.5c-.25-1.25-1.25-2-2.5-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
