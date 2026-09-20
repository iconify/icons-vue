<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wd5_dzm8l"/><path class="wtm0crmwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:collaboraoffice" /></template>
<style>
.wd5_dzm8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.46 34.61L18 43.06a1.48 1.48 0 0 0 2.11 0l18-18a1.49 1.49 0 0 0 0-2.11l-18-18a1.49 1.49 0 0 0-2.12 0l-8.5 8.5");
}

.wtm0crmwk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.46 34.61l9.36-9.36a1.73 1.73 0 0 0 0-2.45l-9.36-9.36Z");
}

</style>
