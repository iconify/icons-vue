<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4rpmybrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:devices-outline-sharp" /></template>
<style>
.q4rpmybrt {
  fill: currentColor;
  d: path("M2 20v-2h10v2zm1-3V4h18v2H5v9h7v2zm17 1v-8h-4v8zm-6 2V8h8v12zm4-7.5q.325 0 .538-.225t.212-.525q0-.325-.213-.537T18 11q-.3 0-.525.213t-.225.537q0 .3.225.525T18 12.5m0 1.5");
}

</style>
