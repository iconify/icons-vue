<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j6emltbaw"/><circle class="ui1zimbxa"/><path class="rpvl7wgpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:complication-box" /></template>
<style>
.j6emltbaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.744 4.5a2.94 2.94 0 0 0-2.865 2.28l-1.31 5.669h.06A14.3 14.3 0 0 0 9.699 24a14.3 14.3 0 0 0 5.928 11.549h-.059l1.31 5.672a2.94 2.94 0 0 0 2.864 2.28h8.514a2.94 2.94 0 0 0 2.865-2.28l1.31-5.674h-.056A14.3 14.3 0 0 0 38.3 24a14.3 14.3 0 0 0-5.87-11.547l-1.31-5.674A2.94 2.94 0 0 0 28.256 4.5z");
}

.rpvl7wgpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.87 21.038L24 24l5.13-2.962L24 18.076zv5.924L24 29.924l5.13-2.962v-5.924L24 24v5.924");
}

.ui1zimbxa {
  cx: 24px;
  cy: 24px;
  r: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
