<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnlvbobrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ac-on" /></template>
<style>
.jnlvbobrs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 18 13H6a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 6 4m0 6h12M7.5 16l-1 4.5M12 16v4.5m4.5-4.5l1 4.5");
}

</style>
