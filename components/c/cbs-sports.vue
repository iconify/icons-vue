<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="rr89qvbde"/><path class="id5dlgb_u"/><circle class="e1o3acqae"/></g><g class="y9tr6bcfx"><path class="u3xzs6b2n"/><rect class="zlccgob1n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cbs-sports" /></template>
<style>
.e1o3acqae {
  cx: 24px;
  cy: 19.706px;
  r: 8.38px;
}

.id5dlgb_u {
  d: path("M24 11.325c-6.402 0-12.01 3.35-15.205 8.38c3.195 5.032 8.803 8.38 15.205 8.38s12.01-3.348 15.206-8.38c-3.196-5.03-8.804-8.38-15.206-8.38");
}

.rr89qvbde {
  cx: 24px;
  cy: 19.706px;
  r: 15.206px;
}

.u3xzs6b2n {
  d: path("M14.352 43.45V37.4h1.98c1.12 0 2.027.91 2.027 2.032s-.907 2.031-2.027 2.031h-1.98m11.101 1.987V37.4h1.98c1.12 0 2.028.91 2.028 2.032s-.908 2.031-2.027 2.031h-1.98m1.98.001l1.98 1.984m.83-6.047h4.007m-2.004 6.049v-6.049M8.914 42.787c.371.483.836.663 1.483.663h.896a1.51 1.51 0 0 0 1.509-1.51v-.006c0-.833-.676-1.508-1.51-1.508h-.987a1.51 1.51 0 0 1-1.51-1.511c0-.836.677-1.514 1.513-1.514h.89c.648 0 1.113.18 1.484.663m22.636 4.723c.37.483.836.663 1.483.663h.896c.833 0 1.508-.676 1.508-1.51v-.006c0-.833-.675-1.508-1.508-1.508h-.988a1.51 1.51 0 0 1-1.51-1.511c0-.836.677-1.514 1.513-1.514h.89c.648 0 1.113.18 1.484.663");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zlccgob1n {
  width: 4.007px;
  height: 6.049px;
  x: 19.824px;
  y: 37.451px;
  rx: 2.004px;
  ry: 2.004px;
}

</style>
