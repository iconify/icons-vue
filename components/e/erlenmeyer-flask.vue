<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xep6ltbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:erlenmeyer-flask" /></template>
<style>
.xep6ltbfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3v5.75l-5 9.75C3.9 19.75 4.6 21 6 21h12c1.4 0 2.1-1.25 1.5-2.5l-5-9.75V3M8 3h8M7 15h10");
}

</style>
