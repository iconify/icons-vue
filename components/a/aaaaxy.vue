<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sm3mikayw"/><path class="sogo4-btl"/><path class="onuhlrrzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aaaaxy" /></template>
<style>
.onuhlrrzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.56 5.5h36.88v32.208h-2.275v2.79h-1.85V42.5H10.14v-2.214H7.41V37.92H5.56z");
}

.sm3mikayw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.604 34.069h4.883V20.876h2.727v2.426h5.4V21.09h-2.122v-2.427h-3.278v-2.638h-2.727v-2.881h-4.883v2.911h-2.7v2.517h-2.698v2.67h-2.639v2.062h5.338v-2.427h2.7z");
}

.sogo4-btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.025 10.17h12.92v2.578h1.668v1.911h2.675v2.669h2.542v12.768h-2.542v2.608h-2.523v2.244H30.55v2.79H17.904v-2.996h-2.426v-2.553h-2.426v-2.184h-2.396V16.873h2.79v-2.092h1.76V12.47h2.82z");
}

</style>
