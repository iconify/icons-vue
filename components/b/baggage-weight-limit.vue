<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2vrz_9qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baggage-weight-limit" /></template>
<style>
.b2vrz_9qr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 9h14l2 11H3Zm4.5-3.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 9l2-2");
}

</style>
