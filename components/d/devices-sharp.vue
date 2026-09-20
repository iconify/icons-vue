<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt_m5s8ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:devices-sharp" /></template>
<style>
.yt_m5s8ho {
  fill: currentColor;
  d: path("M3 17V4h18v2h-9v11zm11 3V8h8v12zM2 20v-2h10v2zm16-7.5q.325 0 .538-.225t.212-.525q0-.325-.213-.537T18 11q-.3 0-.525.213t-.225.537q0 .3.225.525T18 12.5");
}

</style>
