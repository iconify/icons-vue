<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h1f06ztew"/><path class="h-0herkwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bilnet" /></template>
<style>
.h-0herkwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.329 13.492v14.556h7.278M17.736 13.492v14.556m-7.231-7.278a3.64 3.64 0 0 1 0 7.278H4.5V13.492h6.005a3.64 3.64 0 0 1 0 7.278m0 0H4.5");
}

.h1f06ztew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.286 31.84c2.4 3.862 7.893 7.378 9.33 7.853C39.836 31.922 43.5 21.856 43.5 10.756C35.202 8.108 24.1 7.587 16.554 9.29");
}

</style>
