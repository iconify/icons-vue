<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p5stu0b1p"/><path class="c-buuwbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bauhaus" /></template>
<style>
.c-buuwbeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.334 17.722V11.11l6.29-6.61l6.278 6.61v6.61z");
}

.p5stu0b1p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.029 43.5v-9.916l9.595-10.25l9.584 10.25V43.5zM8.793 28.293v-9.251l7.93-7.931l7.943 7.93v9.252z");
}

</style>
