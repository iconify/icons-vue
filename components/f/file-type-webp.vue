<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="svgIDa" x1="596.629" x2="599.481" y1="-820.523" y2="-826.534" gradientTransform="matrix(.366 0 0 -.366 -210.44 -292.295)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zlxvtzyqk"/><stop offset="1" class="uc9p4gi1t"/></linearGradient><linearGradient id="svgIDc" x1="599.996" x2="631.107" y1="-815.078" y2="-868.963" href="#svgIDa"/><linearGradient id="svgIDd" x1="648.158" x2="677.021" y1="-1013.946" y2="-1071.027" gradientTransform="matrix(.347 0 0 -.339 -214.765 -336.913)" gradientUnits="userSpaceOnUse"><stop offset="0" class="c0545lbko"/><stop offset="1" class="stui2mbih"/></linearGradient><radialGradient id="svgIDe" cx="572.646" cy="-769.85" r="14.375" gradientTransform="matrix(.358 0 0 -.358 -181.98 -268.597)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset=".5" class="vncziwbhx"/><stop offset="1" class="mfjh-ccax"/></radialGradient><filter id="svgIDb"><feGaussianBlur stdDeviation="1.275"/></filter></defs><g filter="url(#svgIDb)"><path class="kfu75ibcn"/><path class="b1pvxwb2r"/></g><path fill="url(#svgIDa)" class="kb0nc0rsw"/><path fill="url(#svgIDc)" class="qzzn08jlt"/><path class="q02_93pzg"/><path stroke="url(#svgIDd)" class="j-l77fj3e"/><circle fill="url(#svgIDe)" class="lf680n6_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-webp" /></template>
<style>
.b1pvxwb2r {
  fill: none;
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--2-051px, 2.051px);
  d: path("M4.646 8h22.707a1.976 1.976 0 0 1 1.981 1.971V25.96a1.977 1.977 0 0 1-1.972 1.981H4.646a1.976 1.976 0 0 1-1.98-1.972V9.978A1.976 1.976 0 0 1 4.637 8Z");
}

.c0545lbko {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.549;
}

.j-l77fj3e {
  fill: none;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--3-38px, 3.38px);
  d: path("M5.185 8.7h21.54c1.406 0 1.879.59 1.879 1.835V25.34c0 1.245-.518 1.834-1.879 1.834H5.185c-1.407 0-1.879-.544-1.879-1.834V10.534c0-1.382.609-1.834 1.879-1.834Z");
}

.kb0nc0rsw {
  fill-rule: evenodd;
  stroke: var(--svg-color--366a04, #366a04);
  stroke-width: var(--svg-stroke-width--2-902px, 2.902px);
  d: path("M6.2 6.374h3.281v3.3H6.2Z");
}

.kfu75ibcn {
  fill-rule: evenodd;
  d: path("M4.646 8h22.707a1.976 1.976 0 0 1 1.981 1.971V25.96a1.977 1.977 0 0 1-1.972 1.981H4.646a1.976 1.976 0 0 1-1.98-1.972V9.978A1.976 1.976 0 0 1 4.637 8Z");
}

.lf680n6_s {
  cx: 23.184px;
  cy: 7.22px;
  r: 5.15px;
}

.mfjh-ccax {
  stop-color: var(--svg-color--fff300, #fff300);
  stop-opacity: 0;
}

.q02_93pzg {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--366a04, #366a04);
  stroke-width: var(--svg-stroke-width--3-605px, 3.605px);
  d: path("M20.877 17.969A4.878 4.878 0 1 1 16 13.092a4.877 4.877 0 0 1 4.877 4.877Z");
}

.qzzn08jlt {
  fill-rule: evenodd;
  stroke: var(--svg-color--366a04, #366a04);
  stroke-width: var(--svg-stroke-width--3-605px, 3.605px);
  d: path("M4.646 8h22.707a1.977 1.977 0 0 1 1.981 1.972v15.989a1.977 1.977 0 0 1-1.972 1.98H4.646a1.976 1.976 0 0 1-1.98-1.972V9.978A1.976 1.976 0 0 1 4.638 8h.008Z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.uc9p4gi1t {
  stop-color: var(--svg-color--4e9a06, #4e9a06);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vncziwbhx {
  stop-color: var(--svg-color--fff520, #fff520);
  stop-opacity: 0.891;
}

.zlxvtzyqk {
  stop-color: var(--svg-color--8ae234, #8ae234);
}

</style>
