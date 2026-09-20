<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="ssvg-id-left-pointing-magnifying-glassa" x1="69.845" x2="69.845" y1="72.22" y2="82.027" gradientTransform="rotate(-45.001 68.555 70.065)" gradientUnits="userSpaceOnUse"><stop offset="0" class="rwhk7-m5g"/><stop offset="1" class="xe7cugbhx"/></linearGradient><path fill="url(#ssvg-id-left-pointing-magnifying-glassa)" class="qjq6wjghn"/><path class="ouj70sisj"/><radialGradient id="ssvg-id-left-pointing-magnifying-glassb" cx="43.358" cy="4.333" r="82.01" gradientTransform="matrix(1.0004 0 0 1 -.027 0)" gradientUnits="userSpaceOnUse"><stop offset="0" class="hxbcyprrs"/><stop offset=".227" class="gvrw0ybel"/><stop offset=".494" class="qmsr0pbax"/><stop offset=".779" class="xt9ggsumx"/><stop offset="1" class="xe7cugbhx"/></radialGradient><path fill="url(#ssvg-id-left-pointing-magnifying-glassb)" class="ath7cotxq"/><radialGradient id="ssvg-id-left-pointing-magnifying-glassc" cx="83.25" cy="72.5" r="51.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="gq3zn0bun"/><stop offset=".04" class="s_k0s0bbf"/><stop offset=".517" class="ely4tublb"/><stop offset="1" class="y-6l6_j3n"/></radialGradient><path fill="url(#ssvg-id-left-pointing-magnifying-glassc)" class="byt5scbce"/><path class="eoxnifckr"/><path class="a59k0vl3q"/><radialGradient id="ssvg-id-left-pointing-magnifying-glassd" cx="23.025" cy="23.5" r="65.078" gradientUnits="userSpaceOnUse"><stop offset="0" class="sz1e6kb7h"/><stop offset=".17" class="eb4bi-b_a"/><stop offset=".393" class="y5vl52bov"/><stop offset=".646" class="ppguk6bif"/><stop offset=".919" class="gwo3pnvcj"/><stop offset="1" class="e2543vbpo"/></radialGradient><path fill="url(#ssvg-id-left-pointing-magnifying-glassd)" class="w3hs2r3ah"/><path class="p49ag_bzo"/><radialGradient id="ssvg-id-left-pointing-magnifying-glasse" cx="77.192" cy="74.667" r="12.886" gradientTransform="matrix(1.0004 0 0 1 -.027 0)" gradientUnits="userSpaceOnUse"><stop offset="0" class="hxbcyprrs"/><stop offset="1" class="xe7cugbhx"/></radialGradient><path fill="url(#ssvg-id-left-pointing-magnifying-glasse)" class="alw-_cbnu"/><path class="wm1lpkq7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:left-pointing-magnifying-glass" /></template>
<style>
.a59k0vl3q {
  d: path("M82.78 76c1.51 1.42 3.26 2.49 5.11 3.1 5.72 1.9 12.39 6.39 18.3 12.33 6.64 6.68 11.44 14.29 12.82 20.35l.19.84.61.61.88.89c.42.43.42 1.12 0 1.54l-1.59 1.6-.23.23-.17.28c-.13.2-.26.37-.41.51-.15.15-.31.28-.51.41l-.27.18-.23.23-1.59 1.6a1.042 1.042 0 0 1-1.48 0l-.88-.89-.61-.61-.84-.19c-6.03-1.39-13.59-6.2-20.23-12.88-5.91-5.94-10.38-12.65-12.27-18.4-.61-1.86-1.68-3.64-3.1-5.15l6.5-6.58m-.01-4.25l-10.75 10.8 1.78 1.79c1.21 1.21 2.16 2.67 2.69 4.3 1.96 5.96 6.51 13.06 12.99 19.58 7.31 7.35 15.36 12.23 21.69 13.69l.88.89c.79.8 1.83 1.2 2.87 1.2s2.08-.4 2.87-1.2l1.59-1.6c.37-.24.71-.51 1.02-.81.31-.31.58-.65.81-1.02l1.59-1.6a4.086 4.086 0 0 0 0-5.77l-.88-.89c-1.45-6.36-6.3-14.45-13.61-21.8-6.48-6.52-13.55-11.1-19.48-13.06-1.62-.54-3.07-1.49-4.28-2.71l-1.78-1.79z");
  fill: var(--svg-color--424242, #424242);
  opacity: var(--svg-opacity--0-2, 0.2);
}

.alw-_cbnu {
  d: path("M87.19 77.1L77.2 87.15a2.873 2.873 0 0 1-4.09 0l-.96-.97a2.915 2.915 0 0 1 0-4.11l9.99-10.05a2.873 2.873 0 0 1 4.09 0l.96.97a2.915 2.915 0 0 1 0 4.11z");
}

.ath7cotxq {
  d: path("M73.67 16.02c15.94 16.02 15.94 42 0 58.03s-41.78 16.02-57.72 0-15.94-42 0-58.03 41.78-16.03 57.72 0z");
}

.byt5scbce {
  d: path("M108.32 89.31c-6.48-6.52-13.55-11.1-19.48-13.06-1.62-.54-3.07-1.49-4.28-2.71l-1.78-1.79-10.75 10.8 1.78 1.79c1.21 1.21 2.16 2.67 2.69 4.3 1.96 5.96 6.51 13.06 12.99 19.58 7.31 7.35 15.36 12.23 21.69 13.69l.88.89a4.05 4.05 0 0 0 5.74 0l1.59-1.6c.37-.24.71-.51 1.02-.81.31-.31.58-.65.81-1.02l1.59-1.6a4.086 4.086 0 0 0 0-5.77l-.88-.89c-1.45-6.35-6.3-14.45-13.61-21.8z");
}

.e2543vbpo {
  stop-color: var(--svg-color--4fc3f7, #4FC3F7);
}

.eb4bi-b_a {
  stop-color: var(--svg-color--ade3fc, #ADE3FC);
}

.ely4tublb {
  stop-color: var(--svg-color--ff9800, #FF9800);
}

.eoxnifckr {
  d: path("M44.81 7c10.1 0 19.59 3.95 26.73 11.13 14.75 14.83 14.75 38.97 0 53.8-7.14 7.18-16.63 11.13-26.73 11.13s-19.59-3.95-26.73-11.13c-14.75-14.83-14.75-38.97 0-53.8C25.22 10.95 34.72 7 44.81 7m0-3C34.37 4 23.92 8.01 15.95 16.02c-15.94 16.02-15.94 42 0 58.03 7.97 8.01 18.41 12.02 28.86 12.02s20.89-4.01 28.86-12.02c15.94-16.02 15.94-42 0-58.03A40.58 40.58 0 0 0 44.81 4z");
  fill: var(--svg-color--424242, #424242);
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gq3zn0bun {
  stop-color: var(--svg-color--ffa726, #FFA726);
}

.gvrw0ybel {
  stop-color: var(--svg-color--dbdbdb, #DBDBDB);
}

.gwo3pnvcj {
  stop-color: var(--svg-color--5cc7f8, #5CC7F8);
}

.hxbcyprrs {
  stop-color: var(--svg-color--e0e0e0, #E0E0E0);
}

.ouj70sisj {
  d: path("M64.98 60.37l29.56 29.72-4.22 4.24-29.56-29.72 4.22-4.24m0-4.26l-8.45 8.49 33.79 33.98 8.45-8.49-33.79-33.98z");
  fill: var(--svg-color--424242, #424242);
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p49ag_bzo {
  d: path("M44.73 14.73c8.02 0 15.56 3.14 21.23 8.84 11.72 11.78 11.72 30.96 0 42.74-5.67 5.7-13.21 8.84-21.23 8.84s-15.56-3.14-21.23-8.84c-11.72-11.78-11.72-30.96 0-42.74 5.66-5.7 13.21-8.84 21.23-8.84m0-3c-8.46 0-16.91 3.24-23.36 9.73-12.9 12.97-12.9 34 0 46.98 6.45 6.49 14.91 9.73 23.36 9.73s16.91-3.24 23.36-9.73c12.9-12.97 12.9-34 0-46.98a32.832 32.832 0 0 0-23.36-9.73z");
  fill: var(--svg-color--039be5, #039BE5);
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ppguk6bif {
  stop-color: var(--svg-color--81d4fa, #81D4FA);
}

.qjq6wjghn {
  d: path("M98.78 90.08l-8.45 8.5L56.54 64.6l8.45-8.49z");
}

.qmsr0pbax {
  stop-color: var(--svg-color--cdcdcd, #CDCDCD);
}

.rwhk7-m5g {
  stop-color: var(--svg-color--eee, #eee);
}

.s_k0s0bbf {
  stop-color: var(--svg-color--ffa623, #FFA623);
}

.sz1e6kb7h {
  stop-color: var(--svg-color--b3e5fc, #B3E5FC);
}

.w3hs2r3ah {
  d: path("M68.09 21.46c12.9 12.97 12.9 34 0 46.98s-33.82 12.97-46.72 0-12.9-34 0-46.98 33.82-12.97 46.72 0z");
}

.wm1lpkq7o {
  d: path("M84.18 73.17c.14 0 .4.03.63.26l.96.97c.35.36.35.93 0 1.29l-9.99 10.05c-.23.23-.49.26-.63.26s-.4-.03-.63-.26l-.96-.97a.924.924 0 0 1 0-1.29l9.99-10.05c.23-.22.5-.26.63-.26m0-2c-.74 0-1.48.28-2.04.85l-9.99 10.05a2.915 2.915 0 0 0 0 4.11l.96.97c.56.57 1.3.85 2.04.85s1.48-.28 2.04-.85l9.99-10.05a2.915 2.915 0 0 0 0-4.11l-.96-.97c-.56-.56-1.3-.85-2.04-.85z");
  fill: var(--svg-color--424242, #424242);
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xe7cugbhx {
  stop-color: var(--svg-color--9e9e9e, #9E9E9E);
}

.xt9ggsumx {
  stop-color: var(--svg-color--b5b5b5, #B5B5B5);
}

.y-6l6_j3n {
  stop-color: var(--svg-color--fb8c00, #FB8C00);
}

.y5vl52bov {
  stop-color: var(--svg-color--9dddfb, #9DDDFB);
}

</style>
