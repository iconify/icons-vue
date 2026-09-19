<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s7fqn6bld"/><path class="x6ed6ib7a"/><path class="rv4fcvb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:magiconnect" /></template>
<style>
.rv4fcvb9z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.233 20.133h8.45v14.65h-8.45zm13.691 15.824h9.97");
}

.s7fqn6bld {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.32 17.42v-4.798a3.303 3.303 0 0 1 3.296-3.31h29.88v19.454a3.303 3.303 0 0 1-3.296 3.31H17.412");
}

.x6ed6ib7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.977 17.354l5.583 3.34l-5.583 3.34zM7.16 17.42h8.596c.917 0 1.655.739 1.655 1.656v17.957c0 .917-.738 1.655-1.655 1.655H7.159a1.65 1.65 0 0 1-1.655-1.645V19.076c0-.917.738-1.656 1.655-1.656");
}

</style>
