<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.56 .62)scale(.97252)"><defs><radialGradient id="SVGdi8U0bpt" cx="767.18" cy="5169.54" r="14.99" gradientTransform="matrix(.955 0 0 .962 -718.11 -4953.92)" gradientUnits="userSpaceOnUse"><stop offset="0" class="qajbedrgs"/><stop offset="1" class="sww5exvfm"/></radialGradient></defs><path fill="url(#SVGdi8U0bpt)" class="t03eu_bee"/><path class="hnfa5t57s"/><path class="w_2wfjsid"/><path class="amv3t8b4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-arduino" /></template>
<style>
.amv3t8b4d {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.9 15.8h3.23v1.06H8.9zm11.74 1.05h-1.06V15.7h1.06v-1.07h1.14v1.07h1.07v1.14h-1.07v1.06h-1.14z");
}

.hnfa5t57s {
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--0-12px, 0.12px);
  d: path("M10.58 11.65c2.41-.08 3.36.83 4.6 2.07q.44.42.9.92l.93-1a6.2 6.2 0 0 1 3.25-1.92c1.94-.21 3.12-.13 4.31.81a5 5 0 0 1 2.25 3.9a5.7 5.7 0 0 1-3.25 5.16a6 6 0 0 1-3.91.13a7.7 7.7 0 0 1-3.54-2.99c-1.68 2.15-3.2 3.26-5.24 3.16c-7.45-.35-6.84-10.07-.3-10.25Zm1.66 8a9 9 0 0 0 2.85-2.9c-.74-1.25-2.2-2.83-3.45-3.14a4.3 4.3 0 0 0-3.23.78a3.4 3.4 0 0 0-.76 3.68a3.7 3.7 0 0 0 4.59 1.57Zm-2.98-3.5l3.28.01v1.21H9.25Zm13.45 3.6A3.8 3.8 0 0 0 24.94 17a3.5 3.5 0 0 0-1.87-3.1a3.65 3.65 0 0 0-4.2.72a7 7 0 0 0-1.64 2.15a9 9 0 0 0 1.97 2.48a4 4 0 0 0 3.5.5Zm-1.96-2.37h-1.09v-1.23h1.1v-1.07l1.1-.01v1.09h1.08v1.17l-1.02-.01v1.12h-1.17Z");
  opacity: var(--svg-opacity--0-17, 0.17);
}

.qajbedrgs {
  stop-color: var(--svg-color--36bac0, #36bac0);
}

.sww5exvfm {
  stop-color: var(--svg-color--2d9094, #2d9094);
}

.t03eu_bee {
  stroke: var(--svg-color--02797e, #02797e);
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-14px, 1.14px);
  d: path("M29.65 15.93A13.77 13.77 0 1 1 15.88 2.06a13.8 13.8 0 0 1 13.76 13.87Z");
}

.w_2wfjsid {
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--0-24px, 0.24px);
  d: path("M4.92 16.34c0 5.35 7.35 7.34 10.98 1.9c3.77 5.64 10.83 3.27 10.83-1.9s-7.03-7.68-10.83-1.9C12.3 8.72 4.91 11 4.91 16.34Zm1.93 0c0-3.86 5.45-5.08 7.99 0c-2.59 4.89-8 3.86-8 0Zm10.12 0c2.28-5.18 7.89-3.75 7.87 0s-5.65 4.94-7.87 0Z");
}

</style>
