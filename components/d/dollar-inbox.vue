<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="soxpl6jjl"/><path class="seage8b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dollar-inbox" /></template>
<style>
.seage8b9c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.394 44.203A21.5 21.5 0 1 1 45.46 22.126");
}

.soxpl6jjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.561 30.877c1.08 1.405 2.432 1.928 4.314 1.928h2.605c2.424 0 4.389-1.97 4.389-4.398s-1.965-4.399-4.39-4.399h-2.877c-2.424 0-4.39-1.97-4.39-4.398s1.966-4.399 4.39-4.399h2.605c1.882 0 3.235.523 4.313 1.928m-5.479 17.857V13.004");
}

</style>
