<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-u8r5lll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ac-cool-mode" /></template>
<style>
.q-u8r5lll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v11M7.25 5.75l9.5 5.5m-9.5 0l9.5-5.5M12 17v4.5M9.5 19l2.5 2.5l2.5-2.5");
}

</style>
