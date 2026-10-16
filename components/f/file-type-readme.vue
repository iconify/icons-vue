<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="bdbz9-laa"><path class="xt0o_ibll"/><path class="la352ka1l"/><path class="qay7zzurw"/><path class="baf-fzbtb"/><path class="pdxcnbcog"/><path class="trzv4iqee"/><path class="n7gd2r18x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-readme" /></template>
<style>
.baf-fzbtb {
  stroke-width: var(--svg-stroke-width--2-083px, 2.083px);
  d: path("M29.848 22.498s-6.713.03-9.02 1.016l-2.202 1.06l-2.181 1.394");
}

.bdbz9-laa {
  fill: none;
  stroke: var(--svg-color--755838, #755838);
  stroke-width: var(--svg-stroke-width--1-449px, 1.449px);
}

.la352ka1l {
  stroke-width: var(--svg-stroke-width--2-019px, 2.019px);
  d: path("M2.22 6.166s6.964-.106 9.377.824l2.307 1.008l2.292 1.338");
}

.n7gd2r18x {
  stroke-width: var(--svg-stroke-width--2-027px, 2.027px);
  d: path("m16.012 8.74l.055 18.226");
}

.pdxcnbcog {
  stroke-width: var(--svg-stroke-width--2-019px, 2.019px);
  d: path("M29.78 6.167s-6.964-.106-9.377.824L18.096 8l-2.292 1.338");
}

.qay7zzurw {
  stroke-width: var(--svg-stroke-width--2-001px, 2.001px);
  d: path("M3.206 5.483L3.15 23.227M15.971 8.62l-.055 17.744");
}

.trzv4iqee {
  stroke-width: var(--svg-stroke-width--2-001px, 2.001px);
  d: path("m28.794 5.484l.056 17.744M16.029 8.622l.055 17.744");
}

.xt0o_ibll {
  stroke-width: var(--svg-stroke-width--2-083px, 2.083px);
  d: path("M2.152 22.497s6.713.03 9.02 1.016l2.202 1.06l2.181 1.394");
}

</style>
