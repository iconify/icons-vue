<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x45u9bcqe"/><path class="iuszg328t"/><path class="wxnbxy_tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:access-more" /></template>
<style>
.iuszg328t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.898 9.452l15.599 15.599L24 38.548L10.503 25.051l7.034-7.033");
}

.wxnbxy_tm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.898 3l22.051 22.051L24 45L4.051 25.051l7.034-7.033");
}

.x45u9bcqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 18.011l7.041 7.04L24 32.092l-7.041-7.041z");
}

</style>
