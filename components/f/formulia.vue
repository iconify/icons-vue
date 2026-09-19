<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1vo95f1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:formulia" /></template>
<style>
.n1vo95f1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.102 35.915v-23.83m-11.188 23.83v-23.83m0 23.83H6.674a2.17 2.17 0 0 1-1.64-3.592L12.245 24l-7.21-8.323a2.17 2.17 0 0 1 1.64-3.592H43.5");
}

</style>
