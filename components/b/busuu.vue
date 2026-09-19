<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zffqr29na"/><path class="b_7y0lghi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:busuu" /></template>
<style>
.b_7y0lghi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.278 22.28s-3.06 3.838-6.5 3.838c-3.012 0-9.821-.26-14.273 2.31a11.55 11.55 0 0 0-5.25 5.913");
}

.zffqr29na {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.248 11.935v25.477S7.005 43.5 14.15 43.5h17.663c11.616 0 11.711-19.53 1.453-21.224C38.02 14.958 34.852 4.5 26.466 4.5h-11.67s-7.548.143-7.548 7.434Z");
}

</style>
