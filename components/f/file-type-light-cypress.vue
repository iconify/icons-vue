<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGh2gULjOs" x1="-232.595" x2="-232.531" y1="266.492" y2="266.492" gradientTransform="rotate(-76.525 -14250.722 76079.833)scale(-271.077 271.077)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1" class="l2k064n6d"/></linearGradient><linearGradient id="SVGPiXpcbZp" x1="-232.6" x2="-232.537" y1="267.638" y2="267.638" gradientTransform="rotate(210.83 19870.42 41512.3)scale(-250.185 250.185)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1"/></linearGradient></defs><path class="pbh1wlbuz"/><path class="bqmvq-tqb"/><path class="dm42m2bky"/><path class="fzx1dqakd"/><path class="v9rthibrc"/><path fill="url(#SVGh2gULjOs)" class="qifr3ieqw"/><path fill="url(#SVGPiXpcbZp)" class="tw_0h7bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-cypress" /></template>
<style>
.bqmvq-tqb {
  d: path("m23.471 11.58l-2.624 6.584l-2.64-6.584h-2.16l3.7 8.986l-2.632 6.334l1.885.376l6.508-15.7h-2.037Z");
}

.cxqk8zbds {
  stop-color: var(--svg-color--58d09e, #58d09e);
}

.dm42m2bky {
  d: path("M11.942 13.245a2.6 2.6 0 0 1 2.448 1.592l.036.079l1.841-.62l-.04-.094a4.53 4.53 0 0 0-4.285-2.792a4.6 4.6 0 0 0-3.372 1.318A4.42 4.42 0 0 0 7.2 16.02a4.4 4.4 0 0 0 1.369 3.28a4.6 4.6 0 0 0 3.372 1.319a4.53 4.53 0 0 0 4.285-2.792l.04-.094l-1.844-.621l-.035.083a2.55 2.55 0 0 1-2.446 1.588a2.6 2.6 0 0 1-1.92-.786a2.72 2.72 0 0 1-.778-1.97a2.76 2.76 0 0 1 .778-1.988a2.58 2.58 0 0 1 1.92-.789Z");
}

.fzx1dqakd {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M2.961 19.547a13.4 13.4 0 0 1-.482-3.559a13.52 13.52 0 0 1 8.682-12.533l.681 1.745a11.64 11.64 0 0 0-7.473 10.788a11.5 11.5 0 0 0 .414 3.062Z");
}

.l2k064n6d {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
  stop-opacity: 0;
}

.pbh1wlbuz {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M15.5 2.071A13.938 13.938 0 1 1 2.076 16.495A13.95 13.95 0 0 1 15.5 2.071");
}

.qifr3ieqw {
  d: path("M22.225 25.756a11.567 11.567 0 0 0 4.088-15.149l1.675-.866a13.426 13.426 0 0 1-4.748 17.6l-1.015-1.581Z");
}

.tw_0h7bxc {
  d: path("m17.5 25.949l-.46 1.105a.61.61 0 0 1-.536.377q-.233.01-.471.01a11.736 11.736 0 0 1-11.4-9.009l-1.843.413a13.46 13.46 0 0 0 4.71 7.482a13.7 13.7 0 0 0 8.51 2.987h.028c.182 0 .361 0 .542-.012a2.5 2.5 0 0 0 2.206-1.536l.6-1.444z");
}

.v9rthibrc {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M11.07 3.5a13.61 13.61 0 0 1 16.992 6.4l-1.681.855a11.715 11.715 0 0 0-14.623-5.512z");
}

</style>
