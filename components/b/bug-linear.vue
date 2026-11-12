<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ajqm5cvrg"/><path class="b1-zrccxf"/><path class="v2njeqw1d"/><path class="p44zvobxz"/><path class="tuenvub8e"/><path class="vd3sb4b7o"/><path class="omvpd6bfg"/><path class="qj3dxibfk"/><path class="ns62ywbpo"/><path class="a-4dztb1w"/><path class="q0aad5h6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-linear" /></template>
<style>
.a-4dztb1w {
  d: path("M12 22V15");
}

.ajqm5cvrg {
  d: path("M19 11.9375V15C19 18.866 15.866 22 12 22C8.13401 22 5 18.866 5 15V11.9375C5 9.76288 6.76288 8 8.9375 8H15.0625C17.2371 8 19 9.76288 19 11.9375Z");
}

.b1-zrccxf {
  d: path("M16.5 8.27065V7.5C16.5 5.01472 14.4853 3 12 3C9.51472 3 7.5 5.01472 7.5 7.5V8.27065");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ns62ywbpo {
  d: path("M6.2002 18.9203L3.50036 20.0002");
}

.omvpd6bfg {
  d: path("M17.7998 18.9202L20.4997 20.0002");
}

.p44zvobxz {
  d: path("M5 14H2");
}

.q0aad5h6o {
  d: path("M6.2207 9.08781L3.50067 7.9998");
}

.qj3dxibfk {
  d: path("M17.7803 9.08786L20.5004 7.99981");
}

.tuenvub8e {
  d: path("M14.29 3.62571L16.9996 2");
}

.v2njeqw1d {
  d: path("M19 14H22");
}

.vd3sb4b7o {
  d: path("M9.70996 3.62569L7.00047 2");
}

</style>
