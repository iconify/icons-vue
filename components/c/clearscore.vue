<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yy-qjwb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clearscore" /></template>
<style>
.yy-qjwb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.09 41.593H42.5V5.5H6.408v17.412h7.432v-9.98h21.227V34.16H25.09zm-10.342-3.717a4.624 4.624 0 0 1-9.248 0a4.624 4.624 0 0 1 9.248 0");
}

</style>
