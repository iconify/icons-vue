<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="pw7p-85ys"/><path class="k3sx1jb3z"/></g><path class="v1litcb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:image-edit-sharp" /></template>
<style>
.c7atyebze {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.k3sx1jb3z {
  d: path("m2.75 16.25l4.1-4.1l1.125-1.112L9.1 12.15l5.15 5.15M13 16.05l1.85-1.85l1.125-1.112L17.1 14.2l3.9 3.9");
}

.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.utmrllbfo {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

.v1litcb3u {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.25 19.75l.5-2.25l2.5-2.5l.929-.817l1.75 1.75l-.929.817l-2.5 2.5Zm1-2.75L18 18.75");
}

.wil2krbkc {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
