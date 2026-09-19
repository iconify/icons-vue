<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="d0t_jibpl"/><path class="az2ihrlkw"/><circle class="mzltyebib"/><path class="nv6ucrx0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ambient-music-mod" /></template>
<style>
.az2ihrlkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.998 43.96A11.069 11.069 0 0 0 3.14 29.225m14.008-.095a15.83 15.83 0 0 0-14.642-4.623M20.585 45.23a15.85 15.85 0 0 0-1.115-12.945m.668-6.88a20.48 20.48 0 0 0-14.467-5.957a21 21 0 0 0-2.726.179M25.484 45.45a20.6 20.6 0 0 0 .733-5.457a20.46 20.46 0 0 0-2.3-9.456m.379-14.473h5.606v3.68h-5.606z");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.d0t_jibpl {
  cx: 20.718px;
  cy: 28.956px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mzltyebib {
  cx: 20.718px;
  cy: 28.933px;
  r: 3.578px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nv6ucrx0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.296 19.744v9.189");
}

</style>
