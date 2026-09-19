<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uoz-3bcpo"/><path class="ipj5v0bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jiotv" /></template>
<style>
.ipj5v0bal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 33.49v-23a2 2 0 0 0-2-2h-35a2 2 0 0 0-2 2v23a2 2 0 0 0 2 2h35a2 2 0 0 0 2-2m-25.95 6.02h12.9");
}

.uoz-3bcpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.07 14l13.86 8l-13.86 8z");
}

</style>
