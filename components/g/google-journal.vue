<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s3bv-8a7k"/><path class="c-5-cgbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-journal" /></template>
<style>
.c-5-cgbnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 39.5l-10.53-7.167a6 6 0 0 1-3-5.196V10a1.5 1.5 0 0 1 2.382-1.214L24 16.5l11.15-7.714A1.5 1.5 0 0 1 37.53 10v17.137a6 6 0 0 1-3 5.196L24.001 39.5v-23");
}

.s3bv-8a7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.53 16.5H41c.83 0 1.5.669 1.5 1.5v15.5c0 3.324-2.676 6-6 6h-25c-3.324 0-6-2.676-6-6V18c0-.831.669-1.5 1.5-1.5h3.47");
}

</style>
