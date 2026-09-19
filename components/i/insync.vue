<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lull6czsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:insync" /></template>
<style>
.lull6czsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.91 23.8l-5.551-2.804a.59.59 0 0 1-.326-.53v-5.92c0-.211.113-.407.297-.513L23.703 4.58a.59.59 0 0 1 .594 0l16.373 9.453a.6.6 0 0 1 .297.514v6.533m-6.091 3.908l5.758 2.805c.204.1.333.307.333.534v5.126a.6.6 0 0 1-.297.514L24.297 43.42a.6.6 0 0 1-.594 0L7.33 33.967a.6.6 0 0 1-.297-.514v-6.14m11.977-6.156l9.98 5.686");
}

</style>
