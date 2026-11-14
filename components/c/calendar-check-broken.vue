<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6hsndfbx"/><path class="vx9_11fbh"/><path class="gj_6bpb-k"/><path class="k6lg2pyns"/><path class="y8iy07bqv"/><path class="z4gnbmbjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-check-broken" /></template>
<style>
.gj_6bpb-k {
  d: path("M10.75 8.75H21.965");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6lg2pyns {
  d: path("M7 3.785V2.25");
}

.q6hsndfbx {
  d: path("M17.8438 21.6629C19.2306 21.5429 20.1494 21.2574 20.8284 20.5784C22 19.4069 22 17.5212 22 13.75V11.75C22 7.9788 22 6.0931 20.8284 4.9216C19.6569 3.75 17.7712 3.75 14 3.75H10C6.2288 3.75 4.3431 3.75 3.1716 4.9216C2 6.0931 2 7.9788 2 11.75V13.75C2 17.5212 2 19.4069 3.1716 20.5784C4.3431 21.75 6.2288 21.75 10 21.75H14H14.2459");
}

.vx9_11fbh {
  d: path("M2.03516 8.75H5.87496");
}

.y8iy07bqv {
  d: path("M17 3.785V2.25");
}

.z4gnbmbjf {
  d: path("M9.5 15.4L11.1667 17.25L14.5 13.25");
}

</style>
