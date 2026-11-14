<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtwikhbih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-axe" /></template>
<style>
.gtwikhbih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 14h15v5.5a7.5 2 0 0 1-15 0Zm2.821-5.79l1.874-.661a1.5 1.5 0 0 1 1.955 1.05l.884 3.537A1.5 1.5 0 0 1 10.579 14H7.297a1.5 1.5 0 0 1-1.475-1.768l.522-2.876a1.5 1.5 0 0 1 .977-1.146M10.75 7l9.75-3.5");
}

</style>
