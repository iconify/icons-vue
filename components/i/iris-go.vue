<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="af63-f_ki"/><circle class="n-mvlmb5u"/><path class="pefb8rx2a"/><circle class="hm8w1jxmx"/><path class="y9dy_4sox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iris-go" /></template>
<style>
.af63-f_ki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.575 24.981c0-1.648 1.319-2.983 2.945-2.983m-2.945 0v7.905");
}

.hm8w1jxmx {
  cx: 27.556px;
  cy: 18.343px;
  r: 0.75px;
  fill: currentColor;
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

.n-mvlmb5u {
  cx: 15.229px;
  cy: 18.343px;
  r: 0.75px;
  fill: currentColor;
}

.pefb8rx2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.884 21.998v7.905");
}

.y9dy_4sox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.21 21.998v7.905m4.876-.666c.538.457 1.118.667 2.422.667h.661c1.076 0 1.947-.885 1.947-1.976s-.871-1.977-1.947-1.977h-1.321c-1.076 0-1.947-.885-1.947-1.976s.871-1.977 1.947-1.977h.66c1.304 0 1.885.21 2.423.667");
}

</style>
