<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6n_aozfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flower-pot" /></template>
<style>
.c6n_aozfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25a1.75 1.75 0 0 1 2.75 1.5a1.75 1.75 0 0 1 0 3.5A1.75 1.75 0 0 1 12 9.75a1.75 1.75 0 0 1-2.75-1.5a1.75 1.75 0 0 1 0-3.5A1.75 1.75 0 0 1 12 3.25m0 6.5V13m-5.5 0h11a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 14.5A1.5 1.5 0 0 1 6.5 13m0 3l1.25 5.5h8.5L17.5 16M12 6.5h.01");
}

</style>
