<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dqr5b3cng"/><path class="yp870hbwc"/><path class="oves3nbuq"/><path class="z7o97cyup"/><path class="qk1ykkkcf"/><path class="yjli4ujqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cake-line-duotone" /></template>
<style>
.dqr5b3cng {
  d: path("M4 15.5C5.2 17.1 7.2 17.1 8 15.7C8.9 14.1 11.1 14.1 12 15.7C12.9 17.1 15.1 17.1 16 15.7C16.8 14.1 18.8 14.1 20 15.5M8 10V6.25M12 10V6.25M16 10V6.25");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oves3nbuq {
  d: path("M12 2.5H12.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qk1ykkkcf {
  d: path("M22 21.5H2");
}

.yjli4ujqg {
  d: path("M4 21.5V14C4 12.1144 4 11.1716 4.5858 10.5858C5.1716 10 6.1144 10 8 10H16C17.8856 10 18.8284 10 19.4142 10.5858C20 11.1716 20 12.1144 20 14V21.5");
}

.yp870hbwc {
  d: path("M8 2.5H8.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z7o97cyup {
  d: path("M16 2.5H16.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
