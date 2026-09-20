<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g clip-path="url(#SVGLUOopejA)" transform="translate(2 2)scale(.69998)"><path fill="url(#SVGhDMINdaR)" clip-rule="evenodd" class="adep5xb7u"/><mask id="SVGgFzJ3cRp" width="40" height="41" x="0" y="0" maskUnits="userSpaceOnUse"><circle fill="url(#SVGoz8Dqdmv)" class="e5k1lmb1d"/></mask><g filter="url(#SVGXOORzdjy)" mask="url(#SVGgFzJ3cRp)"><path class="t3h_6fk0s"/></g></g><defs><radialGradient id="SVGhDMINdaR" cx="0" cy="0" r="1" gradientTransform="matrix(39.001 0 0 397.71 4 20)" gradientUnits="userSpaceOnUse"><stop offset="0" class="nhen7bcli"/><stop offset=".47" class="dnv6htbab"/><stop offset="1" class="yy63tgb0a"/></radialGradient><radialGradient id="SVGoz8Dqdmv" cx="0" cy="0" r="1" gradientTransform="matrix(39 0 0 397.7 4 20)" gradientUnits="userSpaceOnUse"><stop offset="0" class="dnv6htbab"/><stop offset=".48" class="nhen7bcli"/><stop offset="1" class="wzjr-9bpt"/></radialGradient><clipPath id="SVGLUOopejA"><path class="o_zi3lcok"/></clipPath><filter id="SVGXOORzdjy" width="60" height="46.57" x="-10" y="3.43" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_115_108" stdDeviation="5"/></filter></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-nitro" /></template>
<style>
.adep5xb7u {
  fill-rule: evenodd;
  d: path("M35.22 7.02A20 20 0 1 0 4.79 32.98A20 20 0 0 0 35.22 7.02m-9.97 10.5a1 1 0 0 1 .88 1.5l-.11.2l-7.55 12.4a.8.8 0 0 1-.66.38h-.72a.76.76 0 0 1-.73-.94l2.05-7.92a1 1 0 0 0-.97-1.25h-3.15a1 1 0 0 1-.97-1.25l3.1-11.96c.1-.4.47-.68.89-.68h3.3a1 1 0 0 1 1 1.14l-.03.14l-1.2 7.07a1 1 0 0 0 .98 1.17z");
}

.dnv6htbab {
  stop-color: var(--svg-color--f27cec, #f27cec);
}

.e5k1lmb1d {
  cx: 20px;
  cy: 20px;
  r: 20px;
}

.nhen7bcli {
  stop-color: var(--svg-color--31b2f3, #31b2f3);
}

.o_zi3lcok {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h146v40H0z");
}

.t3h_6fk0s {
  fill: var(--svg-color--fff, #fff);
  d: path("M1.11 13.43a20 20 0 1 0 37.96.54l-5.82 1.84a13.9 13.9 0 1 1-26.38-.38z");
}

.wzjr-9bpt {
  stop-color: var(--svg-color--7d7573, #7d7573);
}

.yy63tgb0a {
  stop-color: var(--svg-color--fd6641, #fd6641);
}

</style>
