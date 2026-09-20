<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":150,"height":150};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGpqQSdc4W)" class="kxgubd9nj"><path class="pdf1oh0an"/><path class="run5p0qrm"/></g><defs><linearGradient id="SVGVsJwCeot" x1="219.28" x2="112.62" y1="236.67" y2="90.238" gradientTransform="translate(2.439 13.9)scale(.93116)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="vc--wpv5i"/></linearGradient><clipPath id="SVGpqQSdc4W"><path class="w15vjsbhu"/></clipPath></defs><path fill="url(#SVGVsJwCeot)" clip-rule="evenodd" class="xcd_p32nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-vercel-opened" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kxgubd9nj {
  fill: var(--svg-color--666, #666);
}

.pdf1oh0an {
  d: path("M128.44 25.781H85.316l-9.844 19.688H20.16v78.75h118.12V25.781zm0 87.657h-97.5V55.312h97.5zm0-67.969H90.003l4.688-9.844h33.281v9.844z");
}

.run5p0qrm {
  d: path("M120.47 64.219H2.34l17.813 60h118.12z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w15vjsbhu {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h150v150H0z");
}

.xcd_p32nb {
  fill-rule: evenodd;
  d: path("m103.18 66.045l39.283 69.837H63.896z");
}

</style>
