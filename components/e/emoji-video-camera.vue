<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pnrmcdbqr"/><path class="ld8tab2pp"/><path class="gx00n1peq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-video-camera" /></template>
<style>
.gx00n1peq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.283 30.998a3.634 3.634 0 1 0 7.266.003v-.003a3.634 3.634 0 1 0-7.266-.004zM5.5 14.405h2.634v13.75H5.5z");
}

.ld8tab2pp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.134 28.154v12.03H33.79V16.409h-8.724v-2.003H8.3m25.49 9.233l4.535-.004v13.79l-4.535.004m.298-25.157l4.781 5.491l3.63-.593l-6.007-9.354zm4.771 5.491l-4.777 3.772M28.92 16.19l5.168-3.927");
}

.pnrmcdbqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.763 37.295H14.245v-15.76h13.518a2.18 2.18 0 0 1 2.18 2.18v11.399a2.18 2.18 0 0 1-2.18 2.18");
}

</style>
