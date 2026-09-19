<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="bqoyu-bdo"/><path class="rm2xfpbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:brainly" /></template>
<style>
.bqoyu-bdo {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 5.5;
  d: path("m9.332 8.28l22.827-4.172M15.896 43.841l22.827-4.173");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rm2xfpbmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.617 23.054l-9.242 1.696m9.242-1.696a4.482 4.482 0 0 1 5.601 4.403a6.956 6.956 0 0 1-5.601 6.458l-9.242 1.696V13.889l9.242-1.696a4.482 4.482 0 0 1 5.601 4.403a6.956 6.956 0 0 1-5.601 6.458m-10.836-8.873l1.594-.292m-1.594 22.014l1.594-.293");
}

</style>
