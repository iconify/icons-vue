<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxom3cput"/><path class="plqbgebtp"/><path class="ydy9kac4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aaaaxy-alt" /></template>
<style>
.plqbgebtp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.941 17.47v13.06l6.53 6.529h13.058l6.53-6.53V17.471l-6.53-6.53H17.471z");
}

.ydy9kac4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.382 22.912L24 15.294l7.618 7.618M24 15.294v17.412");
}

.yxom3cput {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5v31.559l5.441 5.441H37.06l5.441-5.441V5.5z");
}

</style>
