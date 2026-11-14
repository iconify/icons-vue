<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qjipqpzot"/><path class="qwufe_ayo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garage-door-closed" /></template>
<style>
.qjipqpzot {
  d: path("M12.344 19.5H2.5v-10L11 2.25l8.5 7.25v3.856");
}

.qwufe_ayo {
  d: path("M5.5 19.5v-8.25h11v4.55M5.5 14h11m-11 2.75h6.6M14.75 18l2 2L21 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
