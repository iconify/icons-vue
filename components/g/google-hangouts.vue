<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kz8d9to3k"/><path class="ocn6f3bya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-hangouts" /></template>
<style>
.kz8d9to3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5A16.24 16.24 0 0 0 7.76 20.74c0 8.51 7.74 15.58 16.24 16.18v6.58c8-2.23 16.24-12.47 16.24-22.76S33 4.5 24 4.5");
}

.ocn6f3bya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.73 15.64v6.83h3.41v3.42a3.42 3.42 0 0 0 3.42-3.42v-6.83Zm9.71 0v6.83h3.42v3.42a3.42 3.42 0 0 0 3.41-3.42v-6.83Z");
}

</style>
