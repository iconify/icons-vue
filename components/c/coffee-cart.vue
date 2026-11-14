<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hfzbaxf9c"/><path class="dmye75bxp"/><path class="lm24g-bme"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-cart" /></template>
<style>
.dmye75bxp {
  d: path("M3 6.5v12h18v-12m-18 8h18");
}

.hfzbaxf9c {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0");
}

.lm24g-bme {
  d: path("M5.5 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm10 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-5.25-8.5h3.5l-.5 3h-2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
