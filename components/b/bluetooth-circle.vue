<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="h3py7f4sn"/><path clip-rule="evenodd" class="zo1k_nbcm"/><path class="c9fz2s_sr"/><path class="alfhacw0e"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:bluetooth-circle" /></template>
<style>
.alfhacw0e {
  d: path("M14.526 13.802a1 1 0 1 0-1.195-1.604l-6.965 5.195a1 1 0 0 0 1.196 1.603z");
}

.c9fz2s_sr {
  d: path("M14.526 12.198a1 1 0 1 1-1.195 1.604L6.366 8.607a1 1 0 1 1 1.196-1.603z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.h3py7f4sn {
  fill-rule: evenodd;
  d: path("m14.535 13.795l5.572-4.25a1 1 0 0 0 0-1.59l-5.572-4.25a1 1 0 0 0-1.606.795V13a1 1 0 0 0 1.606.795m.394-7.274L17.85 8.75l-2.922 2.23z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.zo1k_nbcm {
  fill-rule: evenodd;
  d: path("m14.535 22.295l5.572-4.25a1 1 0 0 0 0-1.59l-5.572-4.25A1 1 0 0 0 12.93 13v8.5a1 1 0 0 0 1.606.795m.394-7.274l2.922 2.229l-2.922 2.23z");
}

</style>
