<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGRHe0scpU)" class="k6njwxbih"/><path fill="url(#SVGBs0PBdEl)" class="mut6nztnc"/><path fill="url(#SVGzFmgsdqM)" class="cvm10ia5j"/></g><defs><linearGradient id="SVGRHe0scpU" x1="5.333" x2="16.693" y1="6.667" y2="18.235" gradientUnits="userSpaceOnUse"><stop class="nsij3bu4f"/><stop offset="1" class="pc6twabtt"/></linearGradient><linearGradient id="SVGBs0PBdEl" x1="5.333" x2="21.177" y1="4" y2="8.056" gradientUnits="userSpaceOnUse"><stop class="b21bkob0c"/><stop offset="1" class="j1ybr5z-s"/></linearGradient><linearGradient id="SVGzFmgsdqM" x1="5.867" x2="13.808" y1="18.133" y2="13.504" gradientUnits="userSpaceOnUse"><stop class="dt9chctwi"/><stop offset="1" class="dktnb9shj"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:deso-background" /></template>
<style>
.b21bkob0c {
  stop-color: var(--svg-color--84c3ff, #84c3ff);
}

.cvm10ia5j {
  d: path("m12.187 11.952l-6.854 4.053V20l10.134-6.155z");
}

.dktnb9shj {
  stop-color: var(--svg-color--f6fbff, #f6fbff);
}

.dt9chctwi {
  stop-color: var(--svg-color--a8d5ff, #a8d5ff);
}

.ft5dv1b6b {
  fill: none;
}

.j1ybr5z-s {
  stop-color: var(--svg-color--fbfeff, #fbfeff);
}

.k6njwxbih {
  d: path("M5.333 4v4l10.134 5.845L5.333 20h8.25c2.812 0 5.084-1.973 5.084-4.4V12z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.mut6nztnc {
  d: path("m5.333 4l13.334 8V8.4c0-2.432-2.278-4.4-5.083-4.4z");
}

.nsij3bu4f {
  stop-color: var(--svg-color--3fa3ff, #3fa3ff);
}

.pc6twabtt {
  stop-color: var(--svg-color--f0f8ff, #f0f8ff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
