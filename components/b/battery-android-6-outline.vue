<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq3ox-nbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-6-outline" /></template>
<style>
.fq3ox-nbs {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h13.5q1.25 0 2.125.875T20.5 9v6q0 1.25-.875 2.125T17.5 18zm12-2h1.5q.425 0 .713-.288T18.5 15V9q0-.425-.288-.712T17.5 8H16zm5.5-1.5v-5h.5q.425 0 .713.288T23 10.5v3q0 .425-.288.713T22 14.5z");
}

</style>
