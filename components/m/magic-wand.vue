<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGOafqMcen" x1="50.039" x2="58.797" y1="68.904" y2="68.904" gradientTransform="rotate(45 55.99 74.727)scale(1 1.1165)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="aplh-7tkj"/><stop offset=".775" class="xi4bd6b8m"/><stop offset="1" class="a72as_i6q"/></linearGradient><path fill="url(#SVGOafqMcen)" class="fzat30bpt"/><linearGradient id="SVGqxJKQemp" x1="88.88" x2="95.665" y1="34.518" y2="41.304" gradientUnits="userSpaceOnUse"><stop offset=".262" class="sl8ua6bht"/><stop offset=".466" class="ndo2qobxo"/><stop offset=".822" class="n3oe5lbqh"/><stop offset=".989" class="ip0ngccya"/></linearGradient><path fill="url(#SVGqxJKQemp)" class="c-61i7bxg"/><linearGradient id="SVGSGDYhd3O" x1="13.913" x2="20.715" y1="109.476" y2="116.277" gradientUnits="userSpaceOnUse"><stop offset=".262" class="sl8ua6bht"/><stop offset=".466" class="ndo2qobxo"/><stop offset=".822" class="n3oe5lbqh"/><stop offset=".989" class="ip0ngccya"/></linearGradient><path fill="url(#SVGSGDYhd3O)" class="gqd-wnb0s"/><ellipse transform="rotate(-45 7.8 120.699)" class="uasno3bck"/><linearGradient id="SVGyXBGKdLc" x1="68.386" x2="102.984" y1="60.107" y2="25.509" gradientUnits="userSpaceOnUse"><stop offset="0" class="oeypg3mee"/><stop offset="1" class="juve4xbry"/></linearGradient><path fill="url(#SVGyXBGKdLc)" class="gjiklfbnx"/><linearGradient id="SVGmmqTqd7H" x1="-2.51" x2="21.434" y1="131.003" y2="107.059" gradientUnits="userSpaceOnUse"><stop offset="0" class="t3nqpoxzj"/><stop offset=".186" class="gq2bt7bxm"/><stop offset=".49" class="ra316-byb"/><stop offset=".873" class="y85tv_b_t"/><stop offset="1" class="hnxaxn4zi"/></linearGradient><path fill="url(#SVGmmqTqd7H)" class="y7-kw0bhm"/><radialGradient id="SVGSHaaXcNK" cx="75.918" cy="23.046" r="14.784" gradientTransform="rotate(2.178 75.154 22.985)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o0_-kj7bz"/><stop offset="1" class="zo__s054a"/></radialGradient><path fill="url(#SVGSHaaXcNK)" class="y65_efz5w"/><radialGradient id="SVGTbONtbFm" cx="99.385" cy="64.955" r="11.883" gradientTransform="rotate(-20.09 97.623 67.902)" gradientUnits="userSpaceOnUse"><stop offset="0" class="o0_-kj7bz"/><stop offset="1" class="zo__s054a"/></radialGradient><path fill="url(#SVGTbONtbFm)" class="q89x_spjd"/><radialGradient id="SVGM7kbidml" cx="134.587" cy="-6.354" r="16.452" gradientTransform="matrix(-.2474 .9423 -1.0398 -.1868 134.717 -108.97)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o0_-kj7bz"/><stop offset="1" class="zo__s054a"/></radialGradient><path fill="url(#SVGM7kbidml)" class="ckmf6f1za"/><path class="fy66e4brl"/><radialGradient id="SVGy2OfMeuW" cx="92.761" cy="70.093" r="93.729" gradientTransform="matrix(.8599 .5105 -.306 .5153 34.446 -13.385)" gradientUnits="userSpaceOnUse"><stop offset="0" class="u13m7nbhg"/><stop offset="1" class="y589grvmz"/></radialGradient><path fill="url(#SVGy2OfMeuW)" class="dt8drmbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:magic-wand" /></template>
<style>
.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.aplh-7tkj {
  stop-color: var(--svg-color--616161, #616161);
}

.c-61i7bxg {
  d: path("M100.04 28.46c-2.25-2.25-4.19-2-4.19-2L79.73 42.58c.95-.21 2.62.6 4.11 2.08c1.48 1.48 2.29 3.15 2.08 4.11l16.12-16.12c-.01 0 .25-1.93-2-4.19");
}

.ckmf6f1za {
  d: path("m109.65 11.65l8.43-3.74c.42-.19.79.23.57.63l-4.17 7.68c-.1.18-.08.4.05.54l9.03 8.76c.27.28.04.78-.37.8l-11.08-1.95c-.17.01-.33.11-.42.27l-5.83 10.67c-.22.39-.78.35-.87-.06l-1.14-10.39a.44.44 0 0 0-.39-.33l-9.15-1.49c-.39-.03-.54-.5-.24-.79l7.65-5.88c.11-.11.17-.26.15-.41L100.5 4.38c-.04-.44.51-.73.82-.43l7.82 7.62c.13.12.33.15.51.08");
}

.dt8drmbfr {
  d: path("M67.78 35.64c-11.25 2.62-24.16-5-36.08-3.66c-4.55.6-6.42 6.04-2.05 14.66c8.58 14.77 21.1 23.49 25.72 28.9c-6.21-3.48-18.97-12.65-27.84-21.28c-13.35-12.8-10.88-28.8 1.5-28.75c4.15-.4 12.18 1.6 15.54 2.83c3.31 1.33 14.58 6.24 23.21 7.3");
}

.fy66e4brl {
  fill: var(--svg-color--fdd835, #fdd835);
  d: path("M96.29 26.87c-3.74.96-7.53 1.79-11.4 2.11c-3.87.35-7.8.07-11.62-.62c-3.82-.71-7.57-1.6-11.35-2.3s-7.58-1.26-11.4-1.7c-1.91-.22-3.83-.38-5.74-.57c-1.87-.18-3.72-.13-5.48.28c-1.73.44-3.34 1.27-4.38 2.63c-1.05 1.34-1.55 3.08-1.55 4.87c-.02 3.61 1.43 7.21 3.27 10.46c1.85 3.27 4.28 6.24 6.71 9.21c4.84 5.96 10.07 11.63 15.26 17.34c2.6 2.86 5.2 5.71 7.76 8.61c2.58 2.88 5.07 5.85 7.45 8.91c2.39 3.05 4.66 6.24 6.51 9.7c.46.84.97 1.77 1.12 2.89c.05.57-.01 1.2-.33 1.76s-.85.91-1.36 1.14c-1.05.42-2.09.45-3.09.4c-1-.06-1.98-.22-2.94-.44c-3.82-.93-7.39-2.52-10.83-4.31c-1.72-.9-3.4-1.86-5.05-2.87c-1.64-1.02-3.25-2.1-4.83-3.2c3.28 2.04 6.64 3.94 10.11 5.59c3.47 1.64 7.08 3.07 10.79 3.82c.93.17 1.86.31 2.78.34s1.85-.05 2.59-.37c.36-.17.66-.39.81-.69c.15-.29.19-.66.15-1.05c-.12-.8-.55-1.6-1.04-2.43c-1.87-3.3-4.16-6.38-6.6-9.34c-9.76-11.84-20.88-22.6-30.8-34.54c-2.43-3.01-4.89-6.07-6.82-9.54c-1.9-3.44-3.47-7.26-3.42-11.43c.02-2.06.62-4.23 1.98-5.93c1.35-1.73 3.37-2.73 5.36-3.21c2.01-.44 4.07-.49 6.04-.26c1.92.24 3.85.44 5.77.71c3.84.54 7.66 1.2 11.45 1.99c3.79.8 7.54 1.76 11.29 2.57c3.74.82 7.56 1.25 11.4 1.05c3.83-.18 7.64-.83 11.43-1.58");
}

.fzat30bpt {
  d: path("m10.8 123.89l-6.19-6.2l91.23-91.23l6.19 6.19z");
}

.gjiklfbnx {
  d: path("M95.82 26.48L27.88 94.43c-.76.76.01 2.76 1.72 4.46c1.71 1.71 3.71 2.48 4.46 1.72l67.95-67.95s.42-1.88-1.98-4.21s-4.21-1.97-4.21-1.97");
  opacity: var(--svg-opacity--0-85, 0.85);
}

.gq2bt7bxm {
  stop-color: var(--svg-color--1d2a87, #1d2a87);
  stop-opacity: 0.814;
}

.gqd-wnb0s {
  d: path("M25.1 103.4c-2.25-2.25-4.19-2-4.19-2L4.74 117.56c.95-.21 2.67.56 4.16 2.04c1.48 1.48 2.25 3.21 2.04 4.16l16.16-16.17s.25-1.94-2-4.19");
}

.hnxaxn4zi {
  stop-color: var(--svg-color--3367d6, #3367d6);
  stop-opacity: 0;
}

.ip0ngccya {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
}

.juve4xbry {
  stop-color: var(--svg-color--fada80, #fada80);
}

.n3oe5lbqh {
  stop-color: var(--svg-color--cdcdcd, #cdcdcd);
}

.ndo2qobxo {
  stop-color: var(--svg-color--eaeaea, #eaeaea);
}

.o0_-kj7bz {
  stop-color: var(--svg-color--ffeb3b, #ffeb3b);
}

.oeypg3mee {
  stop-color: var(--svg-color--fada80, #fada80);
  stop-opacity: 0;
}

.q89x_spjd {
  d: path("m90.09 63.26l4.74 2.19c.12.06.26.04.36-.04l4.75-3.59c.25-.19.59.01.57.31l-.45 5.9c-.01.13.05.26.17.33l4.53 2.8c.27.17.2.59-.12.65l-5.68 1.17c-.14.03-.25.13-.28.27l-1.21 5.35c-.07.32-.5.38-.66.09l-2.52-4.61a.36.36 0 0 0-.32-.19l-5.96.19c-.31.01-.48-.35-.29-.59l3.84-4.59c.09-.1.11-.24.06-.37l-2.02-4.82c-.11-.29.2-.59.49-.45");
}

.ra316-byb {
  stop-color: var(--svg-color--243da0, #243da0);
  stop-opacity: 0.51;
}

.sl8ua6bht {
  stop-color: var(--svg-color--f5f5f5, #f5f5f5);
}

.t3nqpoxzj {
  stop-color: var(--svg-color--1a237e, #1a237e);
}

.u13m7nbhg {
  stop-color: var(--svg-color--ffee58, #ffee58);
  stop-opacity: 0;
}

.uasno3bck {
  cx: 7.8px;
  cy: 120.7px;
  fill: var(--svg-color--9e9e9e, #9e9e9e);
  rx: 1.94px;
  ry: 4.38px;
}

.xi4bd6b8m {
  stop-color: var(--svg-color--565656, #565656);
}

.y589grvmz {
  stop-color: var(--svg-color--fdd835, #fdd835);
}

.y65_efz5w {
  d: path("m68.37 18.82l5.98-5.96c.33-.33.9-.06.85.41l-.77 6.99c-.03.27.16.52.44.55l8.56 1.02c.5.06.61.74.14.95l-8.92 3.99c-.13.06-.23.18-.27.32l-2.58 8.85c-.12.43-.7.49-.91.1l-3.99-7.25a.51.51 0 0 0-.48-.26l-7.66.62a.497.497 0 0 1-.39-.85l5.08-4.95c.15-.14.19-.37.11-.56l-2.69-6.15c-.18-.42.25-.85.67-.65l6.29 2.94c.17.08.39.04.54-.11");
}

.y7-kw0bhm {
  d: path("M72.59 49.71L4.65 117.66c-.76.76.01 2.76 1.72 4.46c1.71 1.71 3.71 2.48 4.46 1.72L78.79 55.9s.42-1.88-1.98-4.21c-2.41-2.32-4.22-1.98-4.22-1.98");
  opacity: var(--svg-opacity--0-22, 0.22);
}

.y85tv_b_t {
  stop-color: var(--svg-color--2f5cc7, #2f5cc7);
  stop-opacity: 0.127;
}

.zo__s054a {
  stop-color: var(--svg-color--fbc02d, #fbc02d);
}

</style>
