<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="zgx09o38q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exxen" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zgx09o38q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.44 20.166l4.984 7.668m0-7.668l-4.984 7.668m12.98 0v-7.668l5.08 7.668v-7.668M8.5 24h2.492m1.342 3.834H8.5v-7.668h3.834m2.067 0l4.984 7.668m0-7.668l-4.984 7.668M28.52 24h2.492m1.342 3.834H28.52v-7.668h3.834");
}

</style>
