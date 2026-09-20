<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGL3eT8dEE" x1="49.009" x2="225.83" y1="213.75" y2="129.72" gradientUnits="userSpaceOnUse"><stop offset="0" class="ihp9v4bld"/><stop offset=".24" class="s_y3ovbsy"/><stop offset=".352" class="u6k56-beg"/><stop offset=".494" class="dwc4u9pmz"/><stop offset=".745" class="m3um371oc"/><stop offset="1" class="ogd4x_olp"/></linearGradient><linearGradient id="SVGXdyn1ciA" x1="41.025" x2="156.74" y1="28.344" y2="160.34" gradientUnits="userSpaceOnUse"><stop offset="0" class="ja-uenb8g"/><stop offset="1" class="pocirabxc"/></linearGradient><clipPath id="SVGqpIVPcCN"><path class="ang0-8bkx"/></clipPath></defs><path class="oq8yob30i"/><path class="p-xdadbqx"/><g clip-path="url(#SVGqpIVPcCN)" transform="matrix(.08105 0 0 .08508 12.5 11)"><path fill="url(#SVGL3eT8dEE)" class="lzmzk1bgq"/><path fill="url(#SVGXdyn1ciA)" class="lzmzk1bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-angular-opened" /></template>
<style>
.ang0-8bkx {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h223v236H0z");
}

.dwc4u9pmz {
  stop-color: var(--svg-color--dc087d, #dc087d);
}

.ihp9v4bld {
  stop-color: var(--svg-color--e40035, #e40035);
}

.ja-uenb8g {
  stop-color: var(--svg-color--ff31d9, #ff31d9);
}

.lzmzk1bgq {
  d: path("m222.08 39.192l-8.019 125.92L137.39-.008zm-53.105 162.82l-57.933 33.056l-57.934-33.056l11.783-28.556h92.301zm-57.933-139.34l30.357 73.803H80.684zm-103.1 102.44L.005 39.192L84.695 0z");
}

.m3um371oc {
  stop-color: var(--svg-color--9717e7, #9717e7);
}

.ogd4x_olp {
  stop-color: var(--svg-color--6c00f5, #6c00f5);
}

.oq8yob30i {
  fill: var(--svg-color--ca353c, #ca353c);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.p-xdadbqx {
  fill: var(--svg-color--c9353d, #c9353d);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.pocirabxc {
  stop-color: var(--svg-color--ff5be1, #ff5be1);
  stop-opacity: 0;
}

.s_y3ovbsy {
  stop-color: var(--svg-color--f60a48, #f60a48);
}

.u6k56-beg {
  stop-color: var(--svg-color--f20755, #f20755);
}

</style>
