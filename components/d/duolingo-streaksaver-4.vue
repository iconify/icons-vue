<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ioh_3lbob"/><path class="kr9m-_b1h"/><path class="e9jog_bxy"/><path class="rune-hveu"/><path class="wuya_sbyy"/><path class="y2_3kjfns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:duolingo-streaksaver-4" /></template>
<style>
.e9jog_bxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.077 31.366A8.828 8.828 0 0 0 44.5 26.862v-5.19a8.8 8.8 0 0 0-2.21-5.844c0-1.926-.468-4.617-1.771-4.617s-2.509 1.945-2.509 1.945s.815-4.626-1.524-4.626c-3.327 0-5.084 8.956-12.485 8.956S14.84 8.53 11.515 8.53c-2.34 0-1.524 4.626-1.524 4.626s-1.206-1.945-2.51-1.945s-1.77 2.691-1.77 4.617A8.8 8.8 0 0 0 3.5 21.672v5.19a8.83 8.83 0 0 0 8.828 8.828a8.82 8.82 0 0 0 7.595-4.324");
}

.ioh_3lbob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.53 23.09v2.71H6.25l-.243-2.71");
}

.kr9m-_b1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.68 23.09v2.37c0 .11-.01.23-.02.34m-5.57-2.71v2.37c0 .11.01.23.02.34");
}

.rune-hveu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 31.943l4.9-.694a4.504 4.504 0 0 0-4.9-4.222a4.504 4.504 0 0 0-4.9 4.222z");
}

.wuya_sbyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.578 31.436a3.582 3.582 0 1 1-7.156 0M5.383 23.09h13.4c1.57 0 1.865-.98 1.487-1.96m9.114 1.96v2.71h12.28l.243-2.71");
}

.y2_3kjfns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.234 23.09v2.37c0 .11.01.23.02.34m5.57-2.71v2.37c0 .11-.01.23-.02.34m5.726-2.71h-13.4c-1.57 0-1.864-.98-1.486-1.96M24 22.636v-2.384");
}

</style>
