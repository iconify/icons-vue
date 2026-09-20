<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p9q6hfosz"/><path class="bsnus9a1s"/><path class="liv4y0dff"/><path class="g4urorvmm"/><path class="nxab94oij"/><path class="k7v7ieazx"/><path class="jaq0ar5ed"/><path class="qlcluzkdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:egg" /></template>
<style>
.bsnus9a1s {
  fill: var(--svg-color--87ffff, #87ffff);
  d: path("M18.242 16.727c.337-.837.51-1.731.508-2.633C18.75 10.279 16.528 3 12 3C9.066 3 7.1 6.054 6.08 9.242z");
}

.ft5dv1b6b {
  fill: none;
}

.g4urorvmm {
  fill: var(--svg-color--91dcf1, #91dcf1);
  d: path("M6.08 9.242c-.554 1.733-.83 3.508-.83 4.852c0 1.756.641 3.359 1.696 4.578L8.58 10.78z");
}

.jaq0ar5ed {
  fill: var(--svg-color--3e91ff, #3e91ff);
  d: path("m6.949 18.655l7.85-4.048l-6.218-3.827z");
}

.k7v7ieazx {
  fill: var(--svg-color--44b5fd, #44b5fd);
  d: path("M18.75 14.094a7 7 0 0 1-.508 2.633l-3.45-2.123l3.822-2.32c.09.653.136 1.266.136 1.81");
}

.liv4y0dff {
  fill: var(--svg-color--aff, #aff);
  d: path("M10.097 3.466L8.58 10.782l-2.5-1.54c.781-2.44 2.116-4.803 4.016-5.776");
}

.nxab94oij {
  fill: var(--svg-color--43c6fd, #43c6fd);
  d: path("M18.75 14.094c0 .932-.181 1.821-.509 2.633l-3.43-2.112V4.067c2.639 2.164 3.938 7.109 3.938 10.027");
}

.p9q6hfosz {
  fill: var(--svg-color--0075ff, #0075ff);
  d: path("M18.75 14.094C18.75 17.907 15.728 21 12 21s-6.75-3.092-6.75-6.906C5.25 10.279 7.47 3 12 3s6.75 7.279 6.75 11.094");
}

.qlcluzkdr {
  fill: var(--svg-color--0096ff, #0096ff);
  d: path("M14.812 20.374v-5.758l3.43 2.111a6.86 6.86 0 0 1-3.43 3.647");
}

</style>
