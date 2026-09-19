<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r7a0-nbxt"/><g class="y9tr6bcfx"><circle class="wtx5s2kcn"/><circle class="f3oseibts"/><circle class="ul4jtnb_r"/><circle class="tl3ox2x_d"/><path class="edcw3vcbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:klm" /></template>
<style>
.edcw3vcbn {
  d: path("M13.944 25.184h20.112M24 12.446V8.424m-2.011 2.011h4.022");
}

.f3oseibts {
  cx: 20.648px;
  cy: 17.34px;
  r: 3.352px;
}

.r7a0-nbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.44 28.576v10.982h6.832m4.565-.012v-10.97l6.831 10.982L42.5 28.593v10.965m-37-10.963v10.981m0-3.825l7.344-7.119m0 10.944l-5.626-5.49");
}

.tl3ox2x_d {
  cx: 34.056px;
  cy: 17.34px;
  r: 3.352px;
}

.ul4jtnb_r {
  cx: 27.352px;
  cy: 17.34px;
  r: 3.352px;
}

.wtx5s2kcn {
  cx: 13.944px;
  cy: 17.34px;
  r: 3.352px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
