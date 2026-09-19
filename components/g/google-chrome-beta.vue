<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wh33ozsmf"/><path class="jxje-cb2b"/><circle class="vi_nxfq0r"/><circle class="juhm2m-la"/><path class="qjft6ebez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-chrome-beta" /></template>
<style>
.juhm2m-la {
  cx: 24.18px;
  cy: 24.02px;
  r: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jxje-cb2b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.435 43.324c-10.664 5.203-23.527.776-28.73-9.889s-.776-23.528 9.889-28.73C25.258-.5 38.12 3.928 43.324 14.593a21.49 21.49 0 0 1 .001 18.84");
}

.qjft6ebez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.18 15.02h19.36m-27.154 13.5l-9.68-16.766M31.974 28.52l-9.68 16.766");
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wh33ozsmf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.372 38.5a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3");
}

</style>
