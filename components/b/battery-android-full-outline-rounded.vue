<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_o-_2zwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-full-outline-rounded" /></template>
<style>
.g_o-_2zwl {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h13.5q1.25 0 2.125.875T20.5 9v6q0 1.25-.875 2.125T17.5 18zm17.5-3.5v-5h.5q.425 0 .713.288T23 10.5v3q0 .425-.288.713T22 14.5z");
}

</style>
