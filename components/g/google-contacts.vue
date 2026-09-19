<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pfi0hng6k"/><path class="ivoif8b6j"/><circle class="stdt-acxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-contacts" /></template>
<style>
.ivoif8b6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.847 23.085h8.784c4.826 0 8.744 3.918 8.744 8.744v2.928c0 4.825-3.918 8.743-8.744 8.743h-15.29a2.24 2.24 0 0 1-2.237-2.237V31.83c0-4.826 3.918-8.744 8.743-8.744");
}

.pfi0hng6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.72 23.085h4.433c4.826 0 8.744 3.918 8.744 8.744v2.928c0 4.825-3.918 8.743-8.744 8.743H9.863a2.24 2.24 0 0 1-2.238-2.237V36.18c0-7.227 5.868-13.095 13.095-13.095");
}

.stdt-acxp {
  cx: 23.892px;
  cy: 12.186px;
  r: 7.686px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
