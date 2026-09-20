<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="fmn8yub-d"><path class="zgjwe4bso"/><path class="vbmpc4vea"/><path class="kh7xkvb-b"/><path class="m70c3bbsw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:classipod" /></template>
<style>
.fmn8yub-d {
  fill: none;
  stroke: currentColor;
  stroke-dashoffset: 3;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kh7xkvb-b {
  d: path("M20.965 33.695a2.28 2.28 0 0 1-2.279 2.279a2.28 2.28 0 0 1-2.279-2.279a2.28 2.28 0 0 1 2.28-2.279a2.28 2.28 0 0 1 2.278 2.279M34.058 7.066a2.087 2.087 0 0 1-2.087 2.087a2.087 2.087 0 0 1-2.087-2.087a2.087 2.087 0 0 1 2.087-2.087a2.087 2.087 0 0 1 2.087 2.087m5.314 11.967a2.087 2.087 0 0 1-2.087 2.087a2.087 2.087 0 0 1-2.087-2.087a2.087 2.087 0 0 1 2.087-2.087a2.087 2.087 0 0 1 2.087 2.087m-7.401-9.88v26.16c0 2.226-1.02 3.63-3.136 3.63");
}

.m70c3bbsw {
  d: path("M37.285 21.12v10.736c0 2.119-2.376 4.495-4.495 4.495h-4.046M25.256 5.483a2.239 2.239 0 0 0-3.822 1.583v3.93m4.477-3.93v3.93");
}

.vbmpc4vea {
  d: path("M11.543 13.012H25.83a.91.91 0 0 1 .911.911v9.64a.91.91 0 0 1-.911.91H11.543a.91.91 0 0 1-.912-.91v-9.64a.91.91 0 0 1 .912-.911m13.325 20.683a6.18 6.18 0 0 1-6.182 6.182a6.18 6.18 0 0 1-6.182-6.182a6.18 6.18 0 0 1 6.182-6.182a6.18 6.18 0 0 1 6.182 6.182");
}

.zgjwe4bso {
  d: path("M10.907 10.996h15.558a2.274 2.274 0 0 1 2.28 2.28v27.617a2.274 2.274 0 0 1-2.28 2.28H10.907a2.274 2.274 0 0 1-2.279-2.28V13.276a2.274 2.274 0 0 1 2.28-2.28");
}

</style>
