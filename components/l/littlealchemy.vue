<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="apjty2zsw"/><path class="un6g0kb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:littlealchemy" /></template>
<style>
.apjty2zsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.017 7.19l10.03 27.582a12.1 12.1 0 0 1 .729 4.137a4.6 4.6 0 0 1-1.345 3.247a4.6 4.6 0 0 1-3.247 1.344H15.816a4.6 4.6 0 0 1-3.247-1.345a4.6 4.6 0 0 1-1.345-3.247a12.1 12.1 0 0 1 .729-4.136L21.983 7.19h-1.345a1.345 1.345 0 0 1-1.345-1.345A1.345 1.345 0 0 1 20.638 4.5h6.724a1.345 1.345 0 0 1 1.345 1.345a1.345 1.345 0 0 1-1.345 1.345ZM13.1 31.617h21.8");
}

.un6g0kb-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.522 27.565a1.278 1.278 0 1 0-.374-.904a1.3 1.3 0 0 0 .374.904m4.831-6.074a2.126 2.126 0 1 1 0 1.345a2.15 2.15 0 0 1 0-1.345m-2.37-3.543a.95.95 0 1 0-.279-.672a.96.96 0 0 0 .279.672");
}

</style>
