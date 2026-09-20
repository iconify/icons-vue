<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGF5Gycw6S)" class="wtm4ubcjq"/><path class="av3xtuh-z"/><path fill="url(#SVGF5Gycw6S)" class="k6kbsmbzt"/><defs><linearGradient id="SVGF5Gycw6S" x1="13.43" x2="11.63" y1="3.509" y2="20.234" gradientUnits="userSpaceOnUse"><stop class="b8zi92bls"/><stop offset=".44" class="mzq8igbga"/><stop offset=".65" class="cu0mqembg"/><stop offset=".82" class="e9h66oyth"/><stop offset="1" class="hd3om9x-n"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cpool" /></template>
<style>
.av3xtuh-z {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.687 7.885a4.114 4.114 0 1 0 3.62 6.069l2.263 1.234a6.686 6.686 0 1 1 0-6.377l-2.263 1.234a4.11 4.11 0 0 0-3.62-2.16");
}

.b8zi92bls {
  stop-color: var(--svg-color--23b77f, #23b77f);
}

.cu0mqembg {
  stop-color: var(--svg-color--396cc6, #396cc6);
}

.e9h66oyth {
  stop-color: var(--svg-color--5aa3ea, #5aa3ea);
}

.ft5dv1b6b {
  fill: none;
}

.hd3om9x-n {
  stop-color: var(--svg-color--92f5ea, #92f5ea);
}

.k6kbsmbzt {
  d: path("M13.43 3a9 9 0 0 0 0 18z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mzq8igbga {
  stop-color: var(--svg-color--2857b3, #2857b3);
}

.wtm4ubcjq {
  d: path("M13.43 3a9 9 0 0 0 0 18z");
}

</style>
