<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p_pqg633v"/><path class="o--ndfbhv"/><path class="g6p1lsbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-bubbles" /></template>
<style>
.g6p1lsbpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.938 42.5a7.708 7.708 0 1 0 0-15.417a7.708 7.708 0 0 0 0 15.417");
}

.o--ndfbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.906 26.313c5.747 0 10.406-4.66 10.406-10.407S21.653 5.5 15.906 5.5S5.5 10.16 5.5 15.906s4.66 10.406 10.406 10.406M36.333 24a6.167 6.167 0 1 0 0-12.333a6.167 6.167 0 0 0 0 12.333m-5.395 18.5a7.708 7.708 0 1 0 0-15.417a7.708 7.708 0 0 0 0 15.417");
}

.p_pqg633v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.083 32.55a4.1 4.1 0 0 1 1.612-1.612m4.94-15.032a1.97 1.97 0 0 1 .771-.77m-24.281-2.432a6.6 6.6 0 0 1 2.579-2.579");
}

</style>
