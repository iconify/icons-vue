<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s9ll3_bun"/><circle class="v81cn1b-d"/><path class="ylmgo4brd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cryptomania" /></template>
<style>
.s9ll3_bun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.37 34.75a21.5 21.5 0 1 1 0-21.5");
}

.v81cn1b-d {
  cx: 42.749px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ylmgo4brd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.75 31.5v-9.34a5.66 5.66 0 0 0-11.321 0v9.34m11.321-9.34a5.66 5.66 0 1 1 11.32 0v9.34");
}

</style>
