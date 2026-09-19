<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n-p1pnjre"/><circle class="unzp9u_ch"/><path class="m1brp9bme"/><path class="kxtgv1u_p"/><path class="xsi2dcewf"/><path class="qnx87spoz"/><circle class="puzf6r15j"/><path class="mygfmvbel"/><path class="l1enehb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:happy-wheels" /></template>
<style>
.kxtgv1u_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 44.426c1.924 0 3.072-.198 3.072-.198s8.398-5.308 8.16-11.29c1.823.238 1.15-2.575 1.545-3.921s2.377-3.288 2.377-9.904S34.872 3.426 24 3.426S8.845 12.498 8.845 19.113s1.981 8.557 2.377 9.904s-.277 4.16 1.545 3.921c-.238 5.982 8.16 11.29 8.16 11.29s1.15.198 3.073.198");
}

.l1enehb2h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.095 24.575c.051-8.772-5.333-9.714-11.095-9.714s-11.146.942-11.095 9.714");
}

.m1brp9bme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.343 26.018c-.077-1.069 1.244-3.129 2.749-1.227m9.583 7.322c-.327.099-.465.267-.465.267");
}

.mygfmvbel {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35.322c2.396 0 4.27.66 4.904 1.98c.362-.491.38-1.006.235-1.597c-.37-1.507-2.051-3.081-5.139-2.588c-3.088-.493-4.768 1.081-5.139 2.588c-.145.591-.127 1.106.235 1.598c.633-1.32 2.509-1.981 4.904-1.981m13.658-9.304c.076-1.069-1.245-3.129-2.75-1.227m-9.583 7.322c.327.099.465.267.465.267");
}

.n-p1pnjre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.768 26.257c.964-1.334 3.01-.977 4.186-.396m-5.902-1.703c2.456-3.473 5.255.079 7.962-.232");
}

.puzf6r15j {
  cx: 29.139px;
  cy: 25.886px;
  r: 0.75px;
  fill: currentColor;
}

.qnx87spoz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.232 26.257c-.964-1.334-3.01-.977-4.186-.396m5.902-1.703c-2.456-3.473-5.255.079-7.962-.232");
}

.unzp9u_ch {
  cx: 18.861px;
  cy: 25.886px;
  r: 0.75px;
  fill: currentColor;
}

.xsi2dcewf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.572 27.316C38.762 14.008 29.806 12.22 24 12.22S9.238 14.008 10.428 27.316");
}

</style>
