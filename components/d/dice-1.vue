<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dxtmtubnw"/><path class="hmy5tjbql"/><path class="pq0bx_eco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dice-1" /></template>
<style>
.dxtmtubnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m44.338 29.816l-5.111-20.5L18.889 3.5L3.662 18.184l5.111 20.5L29.111 44.5z");
}

.hmy5tjbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.746 29.13l1.481-19.814l-18.415 1.898l-17.15 6.97l10.61 16.8l14.84 9.516z");
}

.pq0bx_eco {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.746 29.13l-23.475 5.853l6.541-23.77zM20.812 11.215L18.889 3.5m18.857 25.63l6.592.686m-30.067 5.167l-5.498 3.7");
}

</style>
