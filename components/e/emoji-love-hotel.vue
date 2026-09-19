<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z11vjsb5t"/><path class="lk5e73bih"/><path class="kce089n5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-love-hotel" /></template>
<style>
.kce089n5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.207 34.885h7.127V42h-7.127zm10.679-24.03a2.297 2.297 0 0 0-4.264-1.183a2.297 2.297 0 0 0-4.11 2.005c.76 2.185 4.11 4.583 4.11 4.583s3.35-2.398 4.11-4.583c.098-.255.154-.532.154-.822");
}

.lk5e73bih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14 5h19.243v37H14z");
}

.z11vjsb5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.334 23.5H22.91v-3.558M18.633 23.5h-1.426v-3.558M30.036 23.5H28.61v-3.558m-4.276 11.385H22.91v-3.558m-4.277 3.558h-1.426v-3.558m12.829 3.558H28.61v-3.558m1.426 11.385H28.61v-3.558M20.77 42v-7.115");
}

</style>
