<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d8i3t0b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:librefit" /></template>
<style>
.d8i3t0b_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.056 24.045h21.852m3.325-15.457v30.854M42.5 13.9v20.2M9.74 8.558v30.615M5.5 13.96v20.2");
}

</style>
