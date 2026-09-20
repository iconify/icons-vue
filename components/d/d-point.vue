<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tgw1tmjll"/><path class="zap4hetjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:d-point" /></template>
<style>
.tgw1tmjll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24A18.5 18.5 0 1 1 24 5.5h18.5Z");
}

.zap4hetjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.625 22.172A5.625 5.625 0 0 0 24 16.547a5.625 5.625 0 0 0-5.625 5.625v3.656A5.625 5.625 0 0 0 24 31.453a5.625 5.625 0 0 0 5.625-5.625m0 5.605V5.5");
}

</style>
