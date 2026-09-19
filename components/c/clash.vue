<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kv2p5-bmq"/><ellipse class="jr-ywtbsy"/><path class="ckeuugbdq"/><ellipse class="rmvk0zbyl"/><path class="r91czd7_e"/><path class="q9qjsqjpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clash" /></template>
<style>
.ckeuugbdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.19 42.5a89 89 0 0 0 14.681-1.572S40.44 12.372 36.458 5.535c.03-.2-3.59 1.755-4.421 6.266a25.6 25.6 0 0 0-4.848-.47");
}

.jr-ywtbsy {
  cx: 21.24px;
  cy: 20.309px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.671px;
  ry: 2.13px;
}

.kv2p5-bmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.19 42.5a89 89 0 0 1-14.681-1.572S13.94 12.372 17.92 5.535c-.13-.297 2.992 1.212 4.422 6.266a25.6 25.6 0 0 1 4.847-.47");
}

.q9qjsqjpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 5.714;
  d: path("M28.41 26.387a1.467 1.467 0 0 1-1.474-1.472");
}

.r91czd7_e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 5.714;
  d: path("M12.508 40.927c-1.93-.327-4.948-.31-6.04-3.487c-1.067-3.107.438-6.67 3.742-7.045m15.253-4.008a1.467 1.467 0 0 0 1.473-1.472");
}

.rmvk0zbyl {
  cx: 33.14px;
  cy: 20.309px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.671px;
  ry: 2.13px;
}

</style>
