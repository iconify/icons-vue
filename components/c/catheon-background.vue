<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGsc2BzJGz)" class="r4i437pya"/><path class="xjh3y25fa"/><path class="vn4re_blz"/><path class="oalmqibrl"/></g><defs><linearGradient id="SVGsc2BzJGz" x1="18.737" x2="7.292" y1="11.064" y2="11.064" gradientUnits="userSpaceOnUse"><stop class="oc-nycb9h"/><stop offset=".27" class="h_3u90buq"/><stop offset=".71" class="q-3i3v6yd"/><stop offset=".91" class="bsrwokbbv"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:catheon-background" /></template>
<style>
.bsrwokbbv {
  stop-color: var(--svg-color--04145e, #04145e);
}

.ft5dv1b6b {
  fill: none;
}

.h_3u90buq {
  stop-color: var(--svg-color--377ef2, #377ef2);
}

.oalmqibrl {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.75 7.9c0 2.215-2 3.1-3.05 3.1c-.88 0-2.635-.81-4.09-1.625C10.15 8.56 9.01 8 8.485 8c-1.75 0-2.405 1.385-3.07 2.275C6.805 4.67 11.485 4 13.45 4s5.3 1.13 5.3 3.9");
}

.oc-nycb9h {
  stop-color: var(--svg-color--6cdbf5, #6cdbf5);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q-3i3v6yd {
  stop-color: var(--svg-color--1e4da1, #1e4da1);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.vn4re_blz {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.25 11.621c0-.44.115-1.1.175-1.375l.475-1.05l.76-1.15l5.495-1.26l.57 2.78a3.8 3.8 0 0 0-1.72-.565c-.65 0-.745.74-.755 1.01v6.88c0 1.84 1.475 2.77 2.25 3.026c-6.85-1.16-7.25-6.9-7.25-8.296");
}

.xjh3y25fa {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.025 15c-.87 0-.935-.83-.86-1.25l-1.08-.36l-.85 1.96l.515 1.435l2.585 2.795l1.015.3c.15.04.55.12.9.12c4.175 0 5.515-2.565 5.495-3.93c0-.085-.01-.165-.02-.24C18.31 13.13 16.3 13 15.79 13a2.55 2.55 0 0 0-1.29.31C11.65 14.67 11.23 15 11.025 15");
}

</style>
