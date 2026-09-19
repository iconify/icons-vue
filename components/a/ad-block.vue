<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mq9wwvbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ad-block" /></template>
<style>
.mq9wwvbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.663 5.5H16.337L5.5 16.337v15.326L16.337 42.5h15.326L42.5 31.663V16.337zM18 30l12-12m-12 0l12 12");
}

</style>
