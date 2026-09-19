<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ap2wne02n"/><path class="xfr72rbcf"/><circle class="ox0rokbvd"/><path class="aby86_4-l"/><path class="xmf_t_bvd"/><circle class="khe4bvbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lemmy" /></template>
<style>
.aby86_4-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.946 34.997c-5.743-1.472-10.014-6.805-10.014-10.966c0-6.219 5.854-11.264 13.068-11.264s13.068 5.045 13.068 11.264c0 4.16-4.271 9.494-10.014 10.966m7.961-5.469l3.819 1.75m-7.274 1.627l2.481 2.933");
}

.ap2wne02n {
  cx: 24px;
  cy: 33.62px;
  r: 3.351px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.khe4bvbvj {
  cx: 30.163px;
  cy: 27.291px;
  r: 1.954px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ox0rokbvd {
  cx: 17.837px;
  cy: 27.291px;
  r: 1.954px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xfr72rbcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.985 29.528l-3.82 1.75m7.275 1.627l-2.481 2.933M11.12 22.15C7.49 21.696 4 18.541 4 16.03c0-3.442 2.296-5 5.416-5c3.065 0 5.555 2.135 5.632 4.79");
}

.xmf_t_bvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.952 15.82c.077-2.655 2.567-4.79 5.632-4.79c3.12 0 5.416 1.558 5.416 5c0 2.511-3.49 5.666-7.12 6.12");
}

</style>
