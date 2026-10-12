<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtxb43bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lane-assist-sharp" /></template>
<style>
.xtxb43bzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 2.75l-4.25 18.5M17 2.75l4.25 18.5M7.75 17v-3l.42-1.18l.66-1.89l.42-1.18h5.5l.42 1.18l.66 1.89l.42 1.18v4.25h-8.5zm1.5-3h5.5");
}

</style>
