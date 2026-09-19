<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fivlxm_bb"/><path class="eo-hh4ayc"/><path class="ijr5md3_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fischer-econnect" /></template>
<style>
.eo-hh4ayc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.828 31.396a4.67 4.67 0 1 1-.858-6.927m16.222 6.927a4.671 4.671 0 1 1 .04-.046");
}

.fivlxm_bb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.176 41.953a21.498 21.498 0 1 1 24.112-.314");
}

.ijr5md3_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.577 29.35a1.5 1.5 0 1 1 .018-.008m8.551-11.33a1.5 1.5 0 1 1 .018-.007m-1.736 3.855l-2.747-4.15l-4.56 3.274s3.01 1.841 3.01 3.887s-.029 4.677-.029 4.677m-7.466-10.857v2.088s-.248 1.674-2.893 1.715m4.383-8.99l.02-1.82m-1.529 1.923h3.142l-.6 5.105h-2.562m-1.346-5.209l-.02-1.818m1.529 1.922h-3.141l.599 5.105h2.563");
}

</style>
