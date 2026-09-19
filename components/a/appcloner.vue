<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d5mvvuqoo"/><path class="b8kl0-b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:appcloner" /></template>
<style>
.b8kl0-b-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 14.09H22a8.36 8.36 0 0 0-7.88 7.85v12m0 2v6.56m2.48-25.9l14.76 14.76M14.09 24L24 33.91m0-19.82L33.91 24");
}

.d5mvvuqoo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 33.91H26a8.36 8.36 0 0 0 7.88-7.85v-12m0-2V5.5");
}

</style>
