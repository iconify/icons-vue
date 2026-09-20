<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVGb3mJQb8l" cx="-280.55" cy="436.76" r=".04" gradientTransform="matrix(550.5 601.5 467.21 -427.59 -49609.89 355512.47)" gradientUnits="userSpaceOnUse"><stop offset="0" class="meyn3rb-s"/><stop offset="1" class="g5sy6dzke"/></radialGradient></defs><path class="d7md2-u1n"/><path fill="url(#SVGb3mJQb8l)" class="ex5v6m97c"/><path fill="url(#SVGb3mJQb8l)" class="jggvxvbht"/><path fill="url(#SVGb3mJQb8l)" class="orhjuzbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-peeky" /></template>
<style>
.d7md2-u1n {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.1 11h21.49v12.52H5.1z");
}

.ex5v6m97c {
  d: path("M11.13 16.06a.85.85 0 1 1-.84-.9a.87.87 0 0 1 .84.9");
}

.g5sy6dzke {
  stop-color: var(--svg-color--bd00ff, #bd00ff);
}

.jggvxvbht {
  d: path("M20.8 16.06a.85.85 0 1 0 .85-.9a.88.88 0 0 0-.85.9");
}

.meyn3rb-s {
  stop-color: var(--svg-color--0029ff, #0029ff);
}

.orhjuzbba {
  fill-rule: evenodd;
  d: path("M3.52 14.8C3.4 7.28 5.06 1.91 6.37 1.91c1 0 3 1.23 4.83 4.11a14.45 14.45 0 0 1 9.54 0c1.85-2.86 3.82-4.09 4.82-4.09c1.29 0 2.92 5.18 2.86 12.5a9.7 9.7 0 0 1 .16 1.72c0 6-.87 14-12.58 14s-12.58-7.92-12.58-14a10 10 0 0 1 .1-1.35m6.35 3.95a2.79 2.79 0 0 0 2.65-2.9A2.79 2.79 0 0 0 9.87 13a2.79 2.79 0 0 0-2.64 2.9a2.79 2.79 0 0 0 2.64 2.85m5.66 2.38a.28.28 0 0 1 .12-.16c-.88-.32-1.56-1.5-1.15-1.67a5.07 5.07 0 0 1 3.13 0c.32.13-.36 1.48-1.3 1.71a.4.4 0 0 1 .08.12a1.3 1.3 0 0 0 1.37.78a2.1 2.1 0 0 0 .84-.21a1 1 0 0 0 .47-.41a.37.37 0 0 1 .49-.17a.38.38 0 0 1 .17.5a1.74 1.74 0 0 1-.8.74a2.75 2.75 0 0 1-1.15.28a2.14 2.14 0 0 1-1.8-.79a2.17 2.17 0 0 1-1.84.79a2.7 2.7 0 0 1-1.16-.28a1.77 1.77 0 0 1-.81-.74a.39.39 0 0 1 .17-.5a.38.38 0 0 1 .5.17a1 1 0 0 0 .46.41a2.1 2.1 0 0 0 .85.21a1.32 1.32 0 0 0 1.36-.78m6.53-2.38a2.78 2.78 0 0 1-2.64-2.9A2.78 2.78 0 0 1 22.06 13a2.78 2.78 0 0 1 2.64 2.9a2.78 2.78 0 0 1-2.64 2.85");
}

</style>
