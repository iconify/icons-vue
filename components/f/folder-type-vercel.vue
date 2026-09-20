<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":150,"height":150};
const content = `<g class="ft5dv1b6b"><defs><linearGradient id="SVGVsJwCeot" x1="219.28" x2="112.62" y1="236.67" y2="90.238" gradientTransform="translate(2.439 13.9)scale(.93116)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="vc--wpv5i"/></linearGradient></defs><path class="go7ohacdc"/><path fill="url(#SVGVsJwCeot)" clip-rule="evenodd" class="xcd_p32nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-vercel" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.go7ohacdc {
  fill: var(--svg-color--52525b, #52525b);
  d: path("M128.3 25.879H84.707l-9.844 19.688H20.02v78.75h118.12V25.879zm0 19.688H89.863l5.156-9.844H128.3z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.xcd_p32nb {
  fill-rule: evenodd;
  d: path("m103.18 66.045l39.283 69.837H63.896z");
}

</style>
