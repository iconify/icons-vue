<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gbnh3d5px"/><path class="kjnmsbc6l"/><path class="rt4tnccpt"/><path class="ui2fq6hom"/><path class="o4i22rebh"/><path class="msfpmgb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librivox" /></template>
<style>
.gbnh3d5px {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.764 25.966c0-4.489-1.936-5.99-4.764-5.99s-4.764 1.501-4.764 5.99m-.55 0h.55v5.324h0h-.55a1.826 1.826 0 0 1-1.826-1.826v-1.672a1.826 1.826 0 0 1 1.826-1.826m10.628 5.324h-.55h0v-5.324h.55a1.826 1.826 0 0 1 1.826 1.826v1.672a1.826 1.826 0 0 1-1.826 1.826");
}

.kjnmsbc6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.476L12.938 33.58V5.524L24 16.351");
}

.msfpmgb7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 42.476l18.5-4.472V9.948L24 16.351");
}

.o4i22rebh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 42.476l14.875-6.919V7.501L24 16.351");
}

.rt4tnccpt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.476L9.125 35.557V7.501L24 16.351");
}

.ui2fq6hom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 42.476L5.5 38.004V9.948L24 16.351m0 26.125l11.062-8.896V5.524L24 16.351");
}

</style>
