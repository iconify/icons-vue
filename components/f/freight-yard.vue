<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yo450zb2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:freight-yard" /></template>
<style>
.yo450zb2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19M4 3v18.5M20 3v18.5m-11.5-7h7A1.5 1.5 0 0 1 17 16v4a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 20v-4a1.5 1.5 0 0 1 1.5-1.5m.75 0v7m5.5-7v7M12 3v11.5");
}

</style>
