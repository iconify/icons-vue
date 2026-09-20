<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(2 2)"><rect fill="url(#SVGSyDbCdIo)" class="b5w5j364n"/><rect filter="url(#SVGG9tgabpE)" class="zp3i9bz2p"/><rect filter="url(#SVGbbpBpe0w)" class="zddnpr4ja"/><rect fill="url(#SVGQnDRJe3j)" class="bsrlwexql"/><rect fill="url(#SVGL3rxySqX)" class="jde8rjmwe"/></g><defs><linearGradient id="SVGSyDbCdIo" x1="13.575" x2="25.892" y1="0" y2="26.088" gradientUnits="userSpaceOnUse"><stop class="o19ptqc3p"/><stop offset="1" class="cequoob6b"/></linearGradient><linearGradient id="SVGQnDRJe3j" x1="9.296" x2="19.648" y1="7" y2="27.075" gradientUnits="userSpaceOnUse"><stop class="hn2esfblp"/><stop offset="1" class="o19ptqc3p"/></linearGradient><linearGradient id="SVGL3rxySqX" x1="3.462" x2="9.184" y1="14" y2="27.556" gradientUnits="userSpaceOnUse"><stop class="lgwa88bup"/><stop offset="1" class="hn2esfblp"/></linearGradient><filter id="SVGG9tgabpE" width="9.801" height="21.468" x="9.063" y="6.881" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur stdDeviation=".117"/></filter><filter id="SVGbbpBpe0w" width="14.001" height="25.667" x="6.963" y="5.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur stdDeviation="1.167"/></filter></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-powerbi" /></template>
<style>
.b5w5j364n {
  width: 9.333px;
  height: 28px;
  x: 15.13px;
  rx: 1.167px;
}

.bsrlwexql {
  width: 9.334px;
  height: 21px;
  x: 9.296px;
  y: 7px;
  rx: 1.167px;
}

.cequoob6b {
  stop-color: var(--svg-color--c87e0e, #c87e0e);
}

.hn2esfblp {
  stop-color: var(--svg-color--f6d751, #f6d751);
}

.jde8rjmwe {
  width: 9.333px;
  height: 14px;
  x: 3.463px;
  y: 14px;
  rx: 1.167px;
}

.lgwa88bup {
  stop-color: var(--svg-color--f9e589, #f9e589);
}

.o19ptqc3p {
  stop-color: var(--svg-color--e6ad10, #e6ad10);
}

.zddnpr4ja {
  width: 9.334px;
  height: 21px;
  x: 9.296px;
  y: 7px;
  fill-opacity: var(--svg-fill-opacity--0-18, 0.18);
  rx: 1.167px;
}

.zp3i9bz2p {
  width: 9.334px;
  height: 21px;
  x: 9.296px;
  y: 7px;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  rx: 1.167px;
}

</style>
