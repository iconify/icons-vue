<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpjljjogh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:devices-2-outline-sharp" /></template>
<style>
.dpjljjogh {
  fill: currentColor;
  d: path("M2 20V4h20v2H4v12h8v2zm18-2v-8h-4v8zm-6 2V8h8v12zm4-7.5q.325 0 .538-.225t.212-.525q0-.325-.213-.537T18 11q-.3 0-.525.213t-.225.537q0 .3.225.525T18 12.5m0 1.5");
}

</style>
