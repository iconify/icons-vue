<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="i-qat1b3v"/><path class="b_gm09b5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epson-iprint" /></template>
<style>
.b_gm09b5c {
  d: path("M30.635 22.628h-13.43a2.11 2.11 0 0 0-2.107 2.108v8.887c0 1.164.944 2.108 2.108 2.108h13.429a2.11 2.11 0 0 0 2.108-2.108v-8.887a2.11 2.11 0 0 0-2.108-2.108M4.527 20.609h38.75m-25.452 5.354h12.087m-12.087 3.186h12.087m-12.087 3.186h12.087m-3.659-18.472h-4.665a2.11 2.11 0 0 0-2.108 2.108v.92c0 1.164.944 2.108 2.108 2.108h4.664a2.11 2.11 0 0 0 2.109-2.108v-.92a2.11 2.11 0 0 0-2.108-2.108");
}

.i-qat1b3v {
  d: path("M12.495 20.75v7.029l-5.887-.015A2.11 2.11 0 0 1 4.5 25.655V14.377c0-1.164.944-2.108 2.108-2.108h34.784c1.164 0 2.108.944 2.108 2.108v11.278a2.11 2.11 0 0 1-2.108 2.108l-6.278.022l-.019-7.035");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
