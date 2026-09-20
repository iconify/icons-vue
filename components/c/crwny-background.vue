<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG3TdKrd2f)" class="r4i437pya"/><path class="cj3p2yrhr"/></g><defs><linearGradient id="SVG3TdKrd2f" x1="12.006" x2="12.006" y1="4.959" y2="6.425" gradientUnits="userSpaceOnUse"><stop class="nv0g5fsou"/><stop offset="1" class="bj6zwbc6d"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:crwny-background" /></template>
<style>
.bj6zwbc6d {
  stop-color: var(--svg-color--dfaf6e, #dfaf6e);
}

.cj3p2yrhr {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.207 9.068c.213 0 .394.134.469.326c0 0 2.047 5.207 2.564 5.207c.367 0 2.169-4.381 2.169-4.381a.5.5 0 0 1 .458-.31h.272c.203 0 .384.123.458.31c0 0 1.802 4.381 2.17 4.381c.517 0 2.569-5.207 2.569-5.207a.5.5 0 0 1 .464-.326h1.695c.367 0 .613.4.458.757c0 0-.714 3.54-4.36 9.589a.57.57 0 0 1-.464.314h-.234c-.192 0-.224 0-.448-.298a34 34 0 0 1-.362-.522l-.288-.427c-.922-1.386-1.711-2.74-1.711-2.74a.08.08 0 0 0-.16 0s-1.2 2.047-2.361 3.689c-.224.299-.261.299-.453.299h-.235a.56.56 0 0 1-.458-.315c-3.64-6.05-4.36-9.594-4.36-9.594c-.155-.352.09-.752.458-.752zm6.3-4.797c.122 0 .234.06.303.16l.592.88a.43.43 0 0 1 .032.416l-1.343 2.238a.058.058 0 0 1-.107.006l-1.332-2.24a.43.43 0 0 1 .027-.415l.586-.88a.39.39 0 0 1 .309-.165zm-8.155.576l.927.682a.5.5 0 0 1 .144.603l-.89 1.721c-.048.096-.123.15-.25.15c-.096-.022-.171-.14-.176-.251c0 0-.048-.57-.086-1.263A12 12 0 0 1 4 5.732v-.288c0-.234.01-.394.01-.394c-.005-.09.027-.17.107-.214a.21.21 0 0 1 .235.011m15.281 0a.21.21 0 0 1 .235-.01a.24.24 0 0 1 .117.213l.005.469v.213c0 .234 0 .506-.016.762c-.043.693-.09 1.263-.09 1.263c0 .107-.075.224-.176.246c-.102.02-.203-.054-.25-.15l-.891-1.721a.5.5 0 0 1 .15-.603z");
}

.ft5dv1b6b {
  fill: none;
}

.nv0g5fsou {
  stop-color: var(--svg-color--ebd19c, #ebd19c);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
