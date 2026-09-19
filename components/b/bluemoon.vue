<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle transform="rotate(-89.931 24 24)" class="cpk0fnbgt"/><path class="aixi2fz9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bluemoon" /></template>
<style>
.aixi2fz9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.163 32.435c11.66 3.091 11.732 6.914 4.964 10.535A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24c0-6.051 2.5-11.518 6.523-15.425c5.013-4.869 9.17-5.566 7.43 7.42c-1.242 9.276 6.055 14.675 12.71 16.44");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
