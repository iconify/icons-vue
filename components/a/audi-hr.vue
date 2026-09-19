<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o__9i9b5f"/><g class="y9tr6bcfx"><circle class="lll6-hb1v"/><circle class="me4908fpw"/><circle class="zxm6skb7y"/><circle class="qp0u_zz-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audi-hr" /></template>
<style>
.lll6-hb1v {
  cx: 9.567px;
  cy: 24px;
  r: 6.067px;
}

.me4908fpw {
  cx: 19.189px;
  cy: 24px;
  r: 6.067px;
}

.o__9i9b5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.2 33.067v8m5.3-8v8m-5.3-4.015h5.3m2.7 4.015v-8h2.619c1.48 0 2.681 1.203 2.681 2.687s-1.2 2.686-2.681 2.686H39.2m2.627.008l2.611 2.617");
}

.qp0u_zz-s {
  cx: 38.433px;
  cy: 24px;
  r: 6.067px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zxm6skb7y {
  cx: 28.811px;
  cy: 24px;
  r: 6.067px;
}

</style>
