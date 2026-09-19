<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c290k1l3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:color-capture" /></template>
<style>
.c290k1l3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.433 45.438L35.81 24l7.007 12.122A21.5 21.5 0 0 1 25.06 45.5c-11.874 0-21.5-9.626-21.5-21.5s9.626-21.5 21.5-21.5a21.5 21.5 0 0 1 19.38 12.19H19.685m10.75 18.62H5.68m14.005 0L7.308 11.872M14.31 24L26.687 2.562");
}

</style>
