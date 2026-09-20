<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG5bh4cevD)" class="r4i437pya"/><path class="seezkcb3l"/></g><defs><linearGradient id="SVG5bh4cevD" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="yr4-n221q"/><stop offset="1" class="d--je6q6f"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kap-background" /></template>
<style>
.d--je6q6f {
  stop-color: var(--svg-color--d38b3e, #d38b3e);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.seezkcb3l {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.212 9.647L4.942 20l5.27-2.87l.287.16l-.955-3.2l-.47 1.444l-.537-.235l.71-2.188zm7.501 0L19.06 20l-5.398-2.87l-.291.16l.979-3.2l.48 1.444l.55-.235l-.73-2.188l1.069-3.464zM11.999 4l-2.353 7.285l2.353 7.774l2.353-7.774zm-1.652 7.299L12 6.169l1.652 5.13L12 16.734z");
}

.yr4-n221q {
  stop-color: var(--svg-color--dba646, #dba646);
}

</style>
