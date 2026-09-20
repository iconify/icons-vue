<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG8BV2heun)" class="r4i437pya"/><path clip-rule="evenodd" class="a59m5mo_w"/></g><defs><linearGradient id="SVG8BV2heun" x1="14.979" x2="4.774" y1="6" y2="13.269" gradientUnits="userSpaceOnUse"><stop class="jvqgeseku"/><stop offset="1" class="k2nn83bwx"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:flx-background" /></template>
<style>
.a59m5mo_w {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M15.789 4h-1.617l-.753 3.68a4.5 4.5 0 0 0-1.015-.27l.438-2.147h-2.653l-.547 2.661a4.42 4.42 0 0 0-1.343 6.581l-.914 4.463A.855.855 0 0 0 8.215 20h1.612l.808-3.941q.498.132 1.04.152l-.518 2.526h2.653l.712-3.47a4.41 4.41 0 0 0 1.145-5.6l.947-4.631A.854.854 0 0 0 15.784 4zm-4 9.684a1.895 1.895 0 1 0 0-3.79a1.895 1.895 0 0 0 0 3.79");
}

.ft5dv1b6b {
  fill: none;
}

.jvqgeseku {
  stop-color: var(--svg-color--77d8fe, #77d8fe);
}

.k2nn83bwx {
  stop-color: var(--svg-color--4fdf9d, #4fdf9d);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
