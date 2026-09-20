<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rekfzbcdt"/><path class="t_aq4jwou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:betteruntis" /></template>
<style>
.rekfzbcdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37 28.6c-4.7 0-8.5 3.8-8.5 8.5s3.8 8.5 8.5 8.5s8.5-3.8 8.5-8.5s-3.8-8.5-8.5-8.5m0 8.5V31m3.4 9.4L37 37.1M24 5.5v37m-18.5-25h37m-37 13h26.2");
}

.t_aq4jwou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 30.6V9.5c0-2.2-1.8-4-4-4h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h21");
}

</style>
