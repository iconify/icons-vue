<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rseitnhtj"/><path class="hvf028b9w"/><path class="slwdvzb8i"/><ellipse transform="rotate(-80.65 18.724 20)" class="owwuv8o3z"/><ellipse transform="rotate(-75 27.05 20.603)" class="baj47bbar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chiki" /></template>
<style>
.baj47bbar {
  cx: 27.051px;
  cy: 20.602px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.147px;
  ry: 0.874px;
}

.hvf028b9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.777 20.957c.294-1.144 3.27-11.82 11.894-11.82c9.111 0 14.369 6.45 16.485 7.876a12.4 12.4 0 0 0 4.344 2.072a7.26 7.26 0 0 1-5.725 3.998");
}

.owwuv8o3z {
  cx: 18.724px;
  cy: 19.999px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.873px;
  ry: 0.762px;
}

.rseitnhtj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.62 34.868s-3.04-4.812-1.838-9.223s8.532-6.705 14.257-3.152c5.67 3.553 5.804 10.003-.344 10.08c-6.639.082-9.791.143-12.03 2.295Z");
}

.slwdvzb8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.594 19.274s1.894 4.979 1.259 9.056c-.63 4.065 2.573 7.106 2.573 7.106s-3.955.516-4.868-.515m1.036 2.286a10.27 10.27 0 0 0-7.73.516c-3.509 1.927-12.921 2.05-17.042-4.79");
}

</style>
