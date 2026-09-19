<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f3udezb_d"/><path class="qd9u8lbsz"/><path class="lhuo-rbsz"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clear-wave" /></template>
<style>
.f3udezb_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.918c4.858-.266 9.23 5.056 12.956 6.817c5.815 2.75 9.113-2.626 13.077-5.753c4.396-3.47 7.63-3.682 10.966.844");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.lhuo-rbsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 20.419c-2.232 2.89-3.74 9.233-7.152 9.221c-4.264-.014-9.39-6.503-15.044-10.013c-5.757-3.573-10.707-1.45-14.804 3.383");
}

.qd9u8lbsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.503 26.592c6.512 3.968 11.18 3.719 14.82-3.445c2.765-5.445 4.662-10.57 6.807-9.454c3.605 1.876 5.964 14.882 11.147 17.125c1.52.657 2.852-2.428 4.22-4.713");
}

</style>
