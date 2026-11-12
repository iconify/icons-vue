<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="oi2w5wbnm"/><path class="i9yj4w9ut"/><path class="ek9io6nwp"/><path class="l1jaee8aw"/><path class="qzbe3svaa"/><path class="aqu4tlbfi"/><path class="bjodqe8lf"/><path class="m4s68xb5w"/><path class="o1mpawv4s"/><path class="ltujox3iu"/><rect class="yyxp_3bpc"/><rect class="cpoxm4-vd"/><rect class="mez379wvu"/><rect class="jn4he3fze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:barcode-broken" /></template>
<style>
.aqu4tlbfi {
  stroke-linecap: round;
  d: path("M15.2217 13.458L15.2217 4.97852");
}

.bjodqe8lf {
  stroke-linecap: round;
  d: path("M22 18.978L22 17.1064");
}

.cpoxm4-vd {
  width: 0.968px;
  height: 8.501px;
  x: 18.127px;
  y: 4.957px;
  rx: 0.484px;
}

.ek9io6nwp {
  stroke-linecap: round;
  d: path("M5.53906 18.9785L5.53906 17.1064");
}

.i9yj4w9ut {
  stroke-linecap: round;
  d: path("M12.3164 13.458L12.3164 4.97852");
}

.jn4he3fze {
  width: 0.968px;
  height: 1.872px;
  x: 8.443px;
  y: 17.106px;
  rx: 0.484px;
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l1jaee8aw {
  stroke-linecap: round;
  d: path("M5.53906 13.458L5.53906 4.97852");
}

.ltujox3iu {
  stroke-linecap: round;
  d: path("M2.63379 13.458L2.63379 4.97852");
}

.m4s68xb5w {
  stroke-linecap: round;
  d: path("M22 13.458L22 4.97803");
}

.mez379wvu {
  width: 0.968px;
  height: 1.872px;
  x: 18.127px;
  y: 17.106px;
  rx: 0.484px;
}

.o1mpawv4s {
  stroke-linecap: round;
  d: path("M2.63379 18.9785L2.63379 17.1064");
}

.oi2w5wbnm {
  stroke-linecap: round;
  d: path("M12.3164 18.9785L12.3164 17.1064");
}

.qzbe3svaa {
  stroke-linecap: round;
  d: path("M15.2217 18.9785L15.2217 17.1064");
}

.yyxp_3bpc {
  width: 0.968px;
  height: 8.501px;
  x: 8.443px;
  y: 4.957px;
  rx: 0.484px;
}

</style>
