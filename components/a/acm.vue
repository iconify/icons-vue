<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 23.999 24)" class="ly9n9l92j"/><path class="h2tfcc8ai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acm" /></template>
<style>
.h2tfcc8ai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.97 20.03l-3.69 3.69M14.9 6.95l-3.69 3.69m8.05.67l-2.05 2.05m6.41 2.31l-2.06 2.05M41.05 33.1l-3.69 3.69m-5.03-12.41l-2.05 2.06m6.41 2.3l-2.05 2.05M24 16.05l3.63-3.63a3.9 3.9 0 0 1 1.47-.92l9-3.11a1.22 1.22 0 0 1 1.55 1.55l-3.11 9a3.9 3.9 0 0 1-.92 1.47L32 24m-8 8L14 42a1.94 1.94 0 0 1-2.75 0l-5.2-5.2a1.94 1.94 0 0 1 0-2.75l10-10m-7.68 7.63l7.95 7.95M27.2 12.85l7.95 7.95");
}

.ly9n9l92j {
  width: 43.39px;
  height: 11.24px;
  x: 2.3px;
  y: 18.38px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

</style>
