<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmv1vcc-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-lobby" /></template>
<style>
.wmv1vcc-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13h16a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 20 16H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 13m.75-9zA2.25 2.25 0 0 1 7 6.25v4.5A2.25 2.25 0 0 1 4.75 13a2.25 2.25 0 0 1-2.25-2.25v-4.5A2.25 2.25 0 0 1 4.75 4M12 4za2.25 2.25 0 0 1 2.25 2.25v4.5A2.25 2.25 0 0 1 12 13a2.25 2.25 0 0 1-2.25-2.25v-4.5A2.25 2.25 0 0 1 12 4m7.25 0za2.25 2.25 0 0 1 2.25 2.25v4.5A2.25 2.25 0 0 1 19.25 13A2.25 2.25 0 0 1 17 10.75v-4.5A2.25 2.25 0 0 1 19.25 4M4.5 16v5.5m15-5.5v5.5M4.5 19h15");
}

</style>
