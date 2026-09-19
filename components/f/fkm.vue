<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k4p-g0bzm"/><path class="z9nhzab6u"/><path class="v-4z0ac7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fkm" /></template>
<style>
.k4p-g0bzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.72 40.5H9.28a1.78 1.78 0 0 1-1.78-1.78V9.28A1.78 1.78 0 0 1 9.28 7.5h29.44a1.78 1.78 0 0 1 1.78 1.78v29.44a1.78 1.78 0 0 1-1.78 1.78M9.28 7.5v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m-29.44 39v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3");
}

.v-4z0ac7g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.12 31.84L27.36 24l8.13-7.78M27.36 24h-1.97");
}

.z9nhzab6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.72 40.5H9.28a1.78 1.78 0 0 1-1.78-1.78V9.28A1.78 1.78 0 0 1 9.28 7.5h29.44a1.78 1.78 0 0 1 1.78 1.78v29.44a1.78 1.78 0 0 1-1.78 1.78M9.28 7.5v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m-29.44 39v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3m4.2 3v-3m4.21 3v-3M40.5 9.28h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m-3 4.2h3m-3 4.21h3M4.5 9.28h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m-3 4.2h3m-3 4.21h3m8.38-22.56h7.83M14.19 24h5.09m-3.4-7.84l-3.39 15.68m14.59-15.68L23.7 31.84");
}

</style>
