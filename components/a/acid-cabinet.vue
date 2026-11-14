<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l89oeq4-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:acid-cabinet" /></template>
<style>
.l89oeq4-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.15 21.5H3.25v-19h12v9.2m-6-9.2v19M6.5 10v3.5M12 10v3.5m6 1V18m0 3h.01");
}

</style>
