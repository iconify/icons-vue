<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc37bwxjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-frame-alert-rounded" /></template>
<style>
.nc37bwxjb {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h13q.425 0 .713.288T18 7t-.288.713T17 8H4q-.425 0-.712.288T3 9v6q0 .425.288.713T4 16h13q.425 0 .713.288T18 17t-.288.713T17 18zm0-4v-4q0-.425.288-.712T5 9h12q.425 0 .713.288T18 10v4q0 .425-.288.713T17 15H5q-.425 0-.712-.288T4 14m16.288 2.213Q20 15.924 20 15.5t.288-.712T21 14.5t.713.288t.287.712t-.288.713T21 16.5t-.712-.288m0-3.5Q20 12.425 20 12V8q0-.425.288-.712T21 7t.713.288T22 8v4q0 .425-.288.713T21 13t-.712-.288");
}

</style>
