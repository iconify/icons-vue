<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eg5dsjb2v"/><path class="criim5b-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:longshot" /></template>
<style>
.criim5b-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.77 31.65l-.79-2.04l.79-2.05m2.16 4.09l-.79-2.04l.79-2.05m2.16 4.09l-.79-2.04l.79-2.05m2.16 4.09l-.79-2.04l.79-2.05m2.16 4.09l-.8-2.04l.8-2.05m2.16 4.09l-.8-2.04l.8-2.05m2.15 4.09l-.79-2.04l.79-2.05m2.16 4.09l-.79-2.04l.79-2.05m2.16 4.09l-.79-2.04l.79-2.05M12.36 9.82H29.1m-16.74 4.05h9.45m-2.91 9.58h16.74M18.9 39.47h16.74M18.9 35.34h13.82");
}

.eg5dsjb2v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.14 19.19V42a1.54 1.54 0 0 0 1.54 1.54h19.18A1.54 1.54 0 0 0 38.4 42V17.55a1.64 1.64 0 0 0-3.27 0a1.64 1.64 0 1 1-3.27 0V5.64a1.14 1.14 0 0 0-1.14-1.14h-20A1.14 1.14 0 0 0 9.6 5.64v12.41a1.15 1.15 0 0 0 1.14 1.14H33.5M16.14 29.61H38.4");
}

</style>
