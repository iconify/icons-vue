<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p8a0s6bak"/><g class="to-5kdesz"><path class="wfpy3gbmy"/><path class="lw4f_pt4y"/><path class="rtndkv_2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-kash-28" /></template>
<style>
.lw4f_pt4y {
  stroke-linecap: round;
  d: path("M39.9 16.105v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953m-12.96-3l.015 6");
}

.p8a0s6bak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.738 29.659c0-2.074 1.66-3.734 3.595-3.734s3.733 1.66 3.733 3.734c0 .968-.415 1.935-1.106 2.627c-1.521 1.244-6.222 4.84-6.222 4.84h7.328m7.262-5.601h-1.82c-1.54 0-2.8 1.26-2.8 2.8h0c0 1.54 1.26 2.8 2.8 2.8h1.82c1.54 0 2.8-1.26 2.8-2.8h0c0-1.54-1.26-2.8-2.8-2.8m0 0c1.54 0 2.8-1.26 2.8-2.8h0c0-1.54-1.26-2.8-2.8-2.8h-1.82c-1.54 0-2.8 1.26-2.8 2.8h0c0 1.54 1.26 2.8 2.8 2.8");
}

.rtndkv_2k {
  d: path("M39.9 16.105a3.985 3.985 0 1 0 0-7.97c-.086 0-.167.02-.253.025c-.653-2.123-2.608-3.677-4.946-3.677S30.41 6.036 29.755 8.16c-.085-.005-.166-.025-.252-.025a3.985 3.985 0 0 0 0 7.97z");
}

.to-5kdesz {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.wfpy3gbmy {
  stroke-linecap: round;
  d: path("M39.9 19.661h-33m33-3.556v23.412a4 4 0 0 1-4 4h-25a4 4 0 0 1-4-4v-25a4 4 0 0 1 4-4h14.953");
}

</style>
