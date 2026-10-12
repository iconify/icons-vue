<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b958zdbvp"/><path class="f4ch9_bvd"/><rect class="l5j5djbah"/><path class="qv0kq79wi"/><rect class="zqrlnhbrx"/><path class="cxv3ntb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dome" /></template>
<style>
.b958zdbvp {
  d: path("M5.25 16.5a6.75 7.5 0 0 1 13.5 0Z");
}

.cxv3ntb-q {
  d: path("M9.5 18.25v1.5m5-1.5v1.5");
}

.f4ch9_bvd {
  d: path("M12 9c-1.75 2-2.75 4.25-2.75 7.5M12 9c1.75 2 2.75 4.25 2.75 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l5j5djbah {
  width: 2.5px;
  height: 3.5px;
  x: 10.75px;
  y: 5.5px;
  rx: 0.5px;
}

.qv0kq79wi {
  d: path("M12 5.5V2.75");
}

.zqrlnhbrx {
  width: 15.5px;
  height: 4.75px;
  x: 4.25px;
  y: 16.5px;
  rx: 0.75px;
}

</style>
