<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(2.22 1.8)scale(.38356)"><clipPath id="SVGCnRYKeZk"><path class="daai3lbmj"/></clipPath><path class="o5omdjvbi"/><g clip-path="url(#SVGCnRYKeZk)" class="doupcnbrp"><path id="SVGq29nGdQx" class="uz5e5vp5s"/><use x="8" href="#SVGq29nGdQx"/><use x="16" href="#SVGq29nGdQx"/><use x="24" href="#SVGq29nGdQx"/><use x="32" href="#SVGq29nGdQx"/><use x="40" href="#SVGq29nGdQx"/><use x="48" href="#SVGq29nGdQx"/><use x="56" href="#SVGq29nGdQx"/><use x="64" href="#SVGq29nGdQx"/></g><path class="einoedbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-overmind" /></template>
<style>
.daai3lbmj {
  d: path("M29.2 2.18S8.14 12.75 6.74 13.42C2.24 15.66 0 17.9 0 23.52v26.96c0 5.61 2.25 7.87 6.74 10.12L29.2 71.82a14.3 14.3 0 0 0 13.48 0l22.46-11.23c4.5-2.25 6.74-4.5 6.74-10.11V23.52c0-5.67-2.24-7.87-6.74-10.1L42.68 2.18a14.3 14.3 0 0 0-13.48 0");
}

.doupcnbrp {
  fill: var(--svg-color--cf1bf4, #cf1bf4);
}

.einoedbqb {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M36 47c-10 0-14-10-14-10s4-10 14-10s14 10 14 10s-4 10-14 10m0-3a7 7 0 1 0 0-14a7 7 0 0 0 0 14m0-3a4 4 0 1 1 0-8a4 4 0 0 1 0 8");
}

.o5omdjvbi {
  fill: var(--svg-color--9013fe, #9013fe);
  d: path("M30 6s-18.75 9.4-20 10c-4 2-6 4-6 9v24c0 5 2 7.01 6 9.01L30 68q6 3 12 0l20-10c4-2 6-4 6-9V25c0-5.05-2-7.01-6-9L42 6q-6-3-12 0");
}

.uz5e5vp5s {
  d: path("M4 1c0 2.03-.36 2.94-1.66 4.89C.64 8.44 0 10.03 0 13s.64 4.56 2.34 7.1C3.64 22.07 4 22.98 4 25s-.36 2.94-1.66 4.9C.64 32.43 0 34.02 0 37s.64 4.56 2.34 7.1C3.64 46.07 4 46.98 4 49s-.36 2.94-1.66 4.9C.64 56.43 0 58.03 0 61s.64 4.56 2.34 7.11C3.64 70.06 4 70.97 4 73h4c0-2.97-.64-4.56-2.34-7.1C4.36 63.93 4 63.03 4 61s.36-2.94 1.66-4.89C7.36 53.56 8 51.97 8 49s-.64-4.56-2.34-7.1C4.36 39.93 4 39.02 4 37s.36-2.94 1.66-4.9C7.36 29.57 8 27.98 8 25s-.64-4.56-2.34-7.1C4.36 15.93 4 15.02 4 13s.36-2.94 1.66-4.9C7.36 5.57 8 3.97 8 1z");
}

</style>
