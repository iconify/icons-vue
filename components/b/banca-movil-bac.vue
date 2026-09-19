<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mnc4job0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banca-movil-bac" /></template>
<style>
.mnc4job0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.506 33.137L38.5 42.5h-33V12.426L28.373 5.5v27.637h8.597l5.53-9.578l-14.127-10.837m0 20.415L20.92 42.5m7.453-27.788L5.5 25.245m22.873-1.321L5.5 39.85");
}

</style>
