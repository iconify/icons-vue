<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bqsbe-gwl"/><path class="mbmqvdbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:home-plus" /></template>
<style>
.bqsbe-gwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.5a9.25 9.25 0 0 1 9.25 9.25v18.5A9.25 9.25 0 0 1 24 42.5h0a9.25 9.25 0 0 1-9.25-9.25v-18.5A9.25 9.25 0 0 1 24 5.5");
}

.mbmqvdbvg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 14.75h18.5A9.25 9.25 0 0 1 42.5 24h0a9.25 9.25 0 0 1-9.25 9.25h-18.5A9.25 9.25 0 0 1 5.5 24h0a9.25 9.25 0 0 1 9.25-9.25");
}

</style>
