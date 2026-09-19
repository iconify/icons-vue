<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pegi8rpdt"/><path class="w_q7iewlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hac-enc" /></template>
<style>
.pegi8rpdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.681 5.5H41.84v37H30.681zM17.319 16.549V5.5H6.161v37h11.158V31.531");
}

.w_q7iewlh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.16 42.5c4.895-8.76 13.068-13.9 24.52-13.9M6.16 32.956c5.238-7.219 13.068-11.305 24.52-11.305M6.16 23.413c5.58-5.677 13.068-8.712 24.52-8.712");
}

</style>
