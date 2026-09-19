<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g5ghvmm7t"/><path class="r95b5w44m"/><path class="jwv8rk4-q"/><path class="yuoz3cbtr"/><path class="t-6etna8a"/><circle class="ityysac-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-forms" /></template>
<style>
.g5ghvmm7t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.757 6.993h12.657A6.086 6.086 0 0 1 42.5 13.08h0a6.086 6.086 0 0 1-6.085 6.085H23.757a6.086 6.086 0 0 1-6.086-6.085h0a6.086 6.086 0 0 1 6.086-6.086m0 24.342h12.657A6.086 6.086 0 0 1 42.5 37.42h0a6.086 6.086 0 0 1-6.085 6.086H23.757a6.086 6.086 0 0 1-6.086-6.086h0a6.086 6.086 0 0 1 6.086-6.085");
}

.ityysac-j {
  cx: 11.585px;
  cy: 13.079px;
  r: 2.921px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jwv8rk4-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.586 19.165a6.086 6.086 0 0 1 6.085 6.085h0a6.086 6.086 0 0 1-6.085 6.086h0A6.086 6.086 0 0 1 5.5 25.25h0a6.086 6.086 0 0 1 6.086-6.085");
}

.r95b5w44m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.586 31.336a6.086 6.086 0 0 1 6.085 6.085h0a6.086 6.086 0 0 1-6.085 6.086h0A6.086 6.086 0 0 1 5.5 37.42h0a6.086 6.086 0 0 1 6.086-6.085");
}

.t-6etna8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.586 6.993a6.086 6.086 0 0 1 6.085 6.086h0a6.086 6.086 0 0 1-6.085 6.085h0A6.086 6.086 0 0 1 5.5 13.08h0a6.086 6.086 0 0 1 6.086-6.086m12.171 6.085h12.657");
}

.yuoz3cbtr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.757 19.165h12.657A6.086 6.086 0 0 1 42.5 25.25h0a6.086 6.086 0 0 1-6.085 6.086H23.757a6.086 6.086 0 0 1-6.086-6.086h0a6.086 6.086 0 0 1 6.086-6.085m0-12.172h12.657A6.086 6.086 0 0 1 42.5 13.08h0a6.086 6.086 0 0 1-6.085 6.085H23.757a6.086 6.086 0 0 1-6.086-6.085h0a6.086 6.086 0 0 1 6.086-6.086");
}

</style>
