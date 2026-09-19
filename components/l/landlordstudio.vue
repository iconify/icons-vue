<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z6b9g_brl"/><path class="mhim3gp6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:landlordstudio" /></template>
<style>
.mhim3gp6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.816 28.56a2.26 2.26 0 0 1-.001 3.242l-4.427 4.303a1.13 1.13 0 0 1-1.578 0L24 23.632L11.19 36.105a1.13 1.13 0 0 1-1.578 0l-4.427-4.303a2.26 2.26 0 0 1-.002-3.242l17.239-16.79a2.26 2.26 0 0 1 3.156 0zm-7.359-10.691v3.546M17.12 16.934L24 23.632m6.88-6.698L24 23.632");
}

.z6b9g_brl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 29.37l-7.705 7.502h15.41z");
}

</style>
