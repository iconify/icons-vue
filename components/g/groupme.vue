<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihbd2vb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:groupme" /></template>
<style>
.ihbd2vb-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.9 6.594v19.377m8.2-19.377v19.377m5.589-13.788H14.312m19.377 8.2H14.312M4.5 22.123a19.5 19.5 0 0 0 18.403 19.253A19.5 19.5 0 0 0 43.5 22.122");
}

</style>
