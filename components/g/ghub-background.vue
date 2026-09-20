<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="js8ketbgj"/><path class="bs2zr-bjo"/><path class="e0dcwub_b"/><path class="ig3jkmb3d"/><path class="cmo5mnfil"/><path class="x_ryribih"/><path class="ntyw60b0k"/><path class="c8fmrxmvs"/><path class="vst-5hbwv"/><path class="f2qr6qb7x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ghub-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bs2zr-bjo {
  fill: var(--svg-color--42c6ea, #42c6ea);
  d: path("m14 9.327l-2.499-.73L16 5.19z");
}

.c8fmrxmvs {
  fill: var(--svg-color--1d1f50, #1d1f50);
  d: path("M12.998 13.943H4l8 5.35z");
}

.cmo5mnfil {
  fill: var(--svg-color--1b6db7, #1b6db7);
  d: path("m13.002 13.943l1.247-4.131L19.999 12l-7.002 1.943z");
}

.e0dcwub_b {
  fill: var(--svg-color--42aadb, #42aadb);
  d: path("M11.501 8.598L8 6.165l-4 7.779z");
}

.f2qr6qb7x {
  fill: var(--svg-color--7cd1ec, #7cd1ec);
  d: path("M11.501 8.597L8 6.165l8-.975z");
}

.ft5dv1b6b {
  fill: none;
}

.ig3jkmb3d {
  fill: var(--svg-color--2a4d9b, #2a4d9b);
  d: path("M13.75 10.057L4 13.944h8.998z");
}

.js8ketbgj {
  fill: var(--svg-color--c6e9f4, #c6e9f4);
  d: path("M10.25 4.706L8 6.165l8-.974z");
}

.ntyw60b0k {
  fill: var(--svg-color--243e81, #243e81);
  d: path("m12 19.294l1.002-5.35L19.999 12z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vst-5hbwv {
  fill: var(--svg-color--1996ce, #1996ce);
  d: path("m13.75 9.567l-2.249-.97L4 13.944z");
}

.x_ryribih {
  fill: var(--svg-color--2589c9, #2589c9);
  d: path("m20 12l-4-6.81l-1.5 4.137z");
}

</style>
