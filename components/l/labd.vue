<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g3ugikb3e"/><circle class="tj8b-tbhb"/><circle class="sy28tfbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:labd" /></template>
<style>
.g3ugikb3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.95 8.557zl2.46-2.284m-24.819 0l2.46 2.284m24.131 12.685v8.076a14.182 14.182 0 0 1-28.364 0v-8.076m0-2.555v-.005A14.15 14.15 0 0 1 24 4.5a14.15 14.15 0 0 1 14.182 14.182v.005m.001 2.555H9.817m0-2.555h28.366");
}

.sy28tfbol {
  cx: 18.514px;
  cy: 13.041px;
  r: 0.75px;
  fill: currentColor;
}

.tj8b-tbhb {
  cx: 29.486px;
  cy: 13.041px;
  r: 0.75px;
  fill: currentColor;
}

</style>
