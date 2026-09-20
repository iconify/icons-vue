<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGQjk2aetU)" class="r4i437pya"/><path class="orwl5umxy"/><path class="nstlnpw2y"/></g><defs><linearGradient id="SVGQjk2aetU" x1="12" x2="12" y1="5" y2="19" gradientUnits="userSpaceOnUse"><stop class="i3azj5r5m"/><stop offset="1" class="yq6u_xb4h"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hmnd-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i3azj5r5m {
  stop-color: var(--svg-color--b4386c, #b4386c);
}

.nstlnpw2y {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 18.94L12.015 5l-8 13.98c.83-.42 2.15-.976 3.35-.976c.69 0 1.37.19 1.89.335c.31.09.59.16.745.16c1.37 0 2.485-.85 3.04-1.27c.18-.14.3-.23.35-.23c.35 0 .51.256.67.51c.155.25.31.49.64.49c.125 0 .215-.1.315-.21c.125-.135.265-.29.51-.29c.56 0 .935.65 1.085 1c.04-.17.215-.5.57-.5c.265 0 .425.25.56.45c.1.145.18.27.27.27c.08 0 .125-.03.19-.065c.11-.064.265-.15.735-.15c.41 0 .78.2 1.065.435");
}

.orwl5umxy {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 18.93L12.01 5L4 19c.83-.386 2.165-.86 3.365-.86c.69 0 1.37.134 1.89.24c.31.06.59.12.745.12c1.37 0 2.485-.855 3.04-1.276c.18-.134.3-.224.35-.224c.35 0 .51.26.665.51c.16.25.315.494.64.494c.13 0 .22-.1.32-.21c.124-.14.264-.294.51-.294c.56 0 .934.64 1.084.994c.04-.174.215-.49.57-.49c.266 0 .425.245.56.45c.1.14.18.265.27.265c.08 0 .125-.03.19-.065c.11-.07.265-.16.735-.16c.41 0 .775.2 1.06.436z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.yq6u_xb4h {
  stop-color: var(--svg-color--f87056, #f87056);
}

</style>
