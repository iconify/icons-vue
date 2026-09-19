<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u7u_gjbko"/><circle class="op8zyzbqy"/><ellipse transform="rotate(-75.011 29.614 14.17)" class="hdlqhv7lp"/><ellipse transform="rotate(-75.013 18.37 33.67)" class="ki8nb7b3z"/><ellipse transform="rotate(-75.01 35.258 23.95)" class="zt4_-sbxt"/><ellipse transform="rotate(-75.011 12.767 23.962)" class="lzhc9dk6l"/><ellipse transform="rotate(-75.002 29.615 33.736)" class="yo02nl89r"/><ellipse transform="rotate(-74.998 18.369 14.248)" class="z8s6i6bij"/><circle class="w5ky3dbor"/><circle class="tc2lnlbhy"/><circle class="pl__9ibkj"/><path class="i2hup8byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:guncho" /></template>
<style>
.hdlqhv7lp {
  cx: 29.614px;
  cy: 14.17px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.606px;
  ry: 4.602px;
}

.i2hup8byr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.023 14.834l1.239-1.238m-1.239 0l1.239 1.238m-1.239 19.455l1.239-1.238m-1.239 0l1.239 1.238m-18.153-9.67l1.239-1.238m-1.239 0l1.239 1.238");
}

.ki8nb7b3z {
  cx: 18.369px;
  cy: 33.67px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.606px;
  ry: 4.602px;
}

.lzhc9dk6l {
  cx: 12.767px;
  cy: 23.962px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.606px;
  ry: 4.602px;
}

.op8zyzbqy {
  cx: 23.951px;
  cy: 24px;
  r: 2.826px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pl__9ibkj {
  cx: 29.642px;
  cy: 14.215px;
  r: 2.336px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tc2lnlbhy {
  cx: 12.728px;
  cy: 23.96px;
  r: 2.336px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u7u_gjbko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.458 3.052a21.47 21.47 0 0 0-11.382 6.64a5.41 5.41 0 0 1 .322 5.9a5.41 5.41 0 0 1-5.102 2.677A21.5 21.5 0 0 0 2.5 24.01c.004 1.94.27 3.872.794 5.741a5.41 5.41 0 0 1 5.102 2.676a5.41 5.41 0 0 1-.337 5.921c2.819 3.14 6.5 5.38 10.584 6.44a5.41 5.41 0 0 1 4.873-3.085a5.41 5.41 0 0 1 4.952 3.245a21.47 21.47 0 0 0 11.483-6.59a5.41 5.41 0 0 1-.345-5.931a5.41 5.41 0 0 1 5.102-2.676c.522-1.869.789-3.8.792-5.741a21.5 21.5 0 0 0-.794-5.741a5.41 5.41 0 0 1-5.102-2.686a5.41 5.41 0 0 1 .339-5.921a21.47 21.47 0 0 0-10.584-6.44a5.41 5.41 0 0 1-4.873 3.085a5.41 5.41 0 0 1-4.962-3.255z");
}

.w5ky3dbor {
  cx: 29.642px;
  cy: 33.685px;
  r: 2.336px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yo02nl89r {
  cx: 29.615px;
  cy: 33.736px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.606px;
  ry: 4.602px;
}

.z8s6i6bij {
  cx: 18.369px;
  cy: 14.248px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.606px;
  ry: 4.602px;
}

.zt4_-sbxt {
  cx: 35.258px;
  cy: 23.95px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.606px;
  ry: 4.602px;
}

</style>
