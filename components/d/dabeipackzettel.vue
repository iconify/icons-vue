<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="emrxkfbid"/><path class="xc17i9b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dabeipackzettel" /></template>
<style>
.emrxkfbid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.976 24L6.179 5.5v37z");
}

.xc17i9b2g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.976 24h20.846L28.396 5.5H6.179zm0 0h20.846L28.396 42.5H6.179z");
}

</style>
