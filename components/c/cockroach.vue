<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGLrYuPcZV" x1="98.149" x2="107.764" y1="210.735" y2="200.86" gradientTransform="rotate(-7.898 -852.989 480.25)" gradientUnits="userSpaceOnUse"><stop offset=".225" class="gkq8hnbkw"/><stop offset="1" class="rj-md3s9a"/></linearGradient><path fill="url(#SVGLrYuPcZV)" class="k20ui2dyy"/><linearGradient id="SVGE2CAzdWW" x1="68.826" x2="68.826" y1="161.757" y2="220.988" gradientTransform="rotate(-8.748 -774.816 432.988)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="jsq4ikbvo"/><stop offset=".253" class="yz_gy2b2e"/><stop offset=".553" class="jfgbsp1td"/><stop offset=".794" class="rw50bdbub"/><stop offset=".944" class="gkq8hnbkw"/></linearGradient><path fill="url(#SVGE2CAzdWW)" class="fugku_72q"/><linearGradient id="SVGIJTuBdHn" x1="460.22" x2="469.836" y1="-63.101" y2="-72.976" gradientTransform="rotate(97.898 276.553 -106.84)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset=".228" class="gkq8hnbkw"/><stop offset="1" class="rj-md3s9a"/></linearGradient><path fill="url(#SVGIJTuBdHn)" class="b1mv7ujcv"/><linearGradient id="SVG3SSWxESF" x1="434.912" x2="434.912" y1="-106.689" y2="-47.458" gradientTransform="rotate(98.748 274.247 -108.659)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="jsq4ikbvo"/><stop offset=".253" class="yz_gy2b2e"/><stop offset=".554" class="jfgbsp1td"/><stop offset=".795" class="rw50bdbub"/><stop offset=".945" class="gkq8hnbkw"/></linearGradient><path fill="url(#SVG3SSWxESF)" class="i8necbcrs"/><path class="tx_gq1jwb"/><ellipse transform="rotate(-25.804 38.948 45.824)" class="ywye0tbyg"/><ellipse transform="rotate(-63.75 46.456 38.134)" class="tes9dgb5h"/><path class="o2mxooxqg"/><path class="k8skupbfi"/><path class="x0j9b1brc"/><linearGradient id="SVGkih29AcL" x1="67.355" x2="67.355" y1="124.77" y2="69.962" gradientTransform="rotate(-45 56.46 71.495)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="jsq4ikbvo"/><stop offset="1" class="gkq8hnbkw"/></linearGradient><path fill="url(#SVGkih29AcL)" class="a6ac0ubya"/><linearGradient id="SVGHtxaTeQB" x1="439.861" x2="425.082" y1="-54.746" y2="-72.034" gradientTransform="rotate(91.45 248.19 -107.902)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="nhl3e3a7w"/><stop offset="1" class="rj-md3s9a"/></linearGradient><path fill="url(#SVGHtxaTeQB)" class="ukr4qybxt"/><linearGradient id="SVGjmXIqbkL" x1="168.939" x2="154.16" y1="202.799" y2="185.51" gradientTransform="rotate(-1.45 -4736.242 3635.05)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="nhl3e3a7w"/><stop offset="1" class="rj-md3s9a"/></linearGradient><path fill="url(#SVGjmXIqbkL)" class="pbhk4d3rv"/><path class="f9yyaxp_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:cockroach" /></template>
<style>
.a6ac0ubya {
  d: path("M78.09 56.62c-3.19-2.33-6.98-2.22-6.98-2.22s-3.9 6.85-6.63 9.72c-2.87 2.73-9.72 6.63-9.72 6.63s-.11 3.79 2.22 6.98s8.49 9.12 13.42 13.32c5.11 4.35 30.82 28.6 40.21 19.21S95.75 75.16 91.4 70.05c-4.19-4.95-10.12-11.1-13.31-13.43");
}

.b1mv7ujcv {
  d: path("M73.55 78.02L48.73 49.84l.62-.9l11.22-7.02s2.84-6.29 2.65-7.05c-.19-.75-9.52-9.46-9.93-10.68s.14-4.7.46-6.48c.26-1.42.9-6.11 2.76-5.72c1.06.22 1.68 2.05 1.33 4.55c-.32 2.29-.54 4.43-.54 4.43s11.04 10.54 11.53 12.21c.5 1.67-.78 7.74-1.59 10.39c-.8 2.65-3.12 8.87-3.12 8.87l3.93-2.65s8.41-9.81 10.05-10.09s14.93 5.56 16.5 5.78s5.19-.73 9.38-.59c4.19.15 10.65-.17 9.48 1.9c-.77 1.35-8.43 2.1-12.43 2.64c-2.77.37-6.51.84-8.39.73c-1.87-.11-11.84-3.68-12.34-3.75s-3.71 6.32-4.54 7.07c-.83.76-3.7 2.54-3.7 2.54l4.51 3.1s13.98-4.97 15.97-4.69c2 .28 7.64 8.77 9.54 10.78s3.79 2.92 6.14 3.9c3.37 1.41 8.17 3.97 10.08 5.4c1.76 1.31 4.76 5.23 5.08 6.52c.65 2.63-6.22-1.95-12.36-4.84s-9.72-3.82-11.14-4.6s-7.41-9.32-8.27-9.44s-9.13 4.63-9.13 4.63z");
}

.f9yyaxp_u {
  fill: var(--svg-color--51362d, #51362d);
  d: path("M68.83 51.86s-1.96 6.94-5.5 10.77c-3.33 3.61-10.44 6.28-10.44 6.28s-.01.91.34 1.55c.35.63.97 1.26 1.71 1.33c1.08.11 8.05-2.94 11.87-7.57s5.95-10.52 3.79-11.89c-1.18-.74-1.77-.47-1.77-.47");
}

.fugku_72q {
  d: path("M36.75 41.47s-.64 2.49-1.51 3.97c-.14.25-12.56-8.68-21.29-3.25c-13.48 8.37 1.56 33.8.01 45.79c-1.08 8.37-3.95 10.19-4.81 9.77c-1.36-.66 2.77-4.12 1.36-15.16c-1.6-12.48-12.87-33.18-.16-42.61c12.38-9.19 26.4 1.49 26.4 1.49");
}

.gkq8hnbkw {
  stop-color: var(--svg-color--814d3c, #814d3c);
}

.i8necbcrs {
  d: path("M41.84 36.38s2.49-.64 3.97-1.51c.25-.14-8.68-12.56-3.25-21.29c8.37-13.48 33.8 1.56 45.79.01c8.37-1.08 10.19-3.95 9.77-4.81c-.66-1.38-4.12 2.76-15.16 1.35c-12.48-1.59-33.17-12.87-42.61-.15c-9.19 12.38 1.49 26.4 1.49 26.4");
}

.jfgbsp1td {
  stop-color: var(--svg-color--a15e47, #a15e47);
}

.jsq4ikbvo {
  stop-color: var(--svg-color--cf7756, #cf7756);
}

.k20ui2dyy {
  d: path("M78.4 73.18L50.21 48.36l-.9.62l-7.02 11.22s-6.29 2.84-7.05 2.65c-.75-.19-9.46-9.52-10.68-9.93s-4.7.14-6.48.46c-1.42.26-6.11.9-5.72 2.76c.22 1.06 2.05 1.68 4.55 1.33c2.29-.32 4.43-.54 4.43-.54s10.54 11.04 12.21 11.53c1.67.5 7.74-.78 10.39-1.59c2.65-.8 8.87-3.12 8.87-3.12l-2.65 3.93s-9.81 8.41-10.09 10.05s5.56 14.93 5.78 16.5s-.73 5.19-.59 9.38c.15 4.19-.17 10.65 1.9 9.48c1.35-.77 2.1-8.43 2.64-12.43c.37-2.77.84-6.51.73-8.39c-.11-1.87-3.68-11.84-3.75-12.34s6.32-3.71 7.07-4.54c.76-.83 2.54-3.7 2.54-3.7l3.1 4.51s-4.97 13.98-4.69 15.97c.28 2 8.77 7.64 10.78 9.54s2.92 3.79 3.9 6.14c1.41 3.37 3.97 8.17 5.4 10.08c1.31 1.76 5.23 4.76 6.52 5.08c2.63.65-1.95-6.22-4.84-12.36s-3.82-9.72-4.6-11.14s-9.32-7.41-9.44-8.27s4.63-9.13 4.63-9.13z");
}

.k8skupbfi {
  fill: var(--svg-color--734434, #734434);
  d: path("M62.89 43.2c-6.75-5.69-14.32-3.02-18.32.91c-3.94 4.01-6.6 11.57-.91 18.32c6.59 7.83 12.43 6.12 12.43 6.12l8.23-4.69l4.69-8.23s1.7-5.84-6.12-12.43");
}

.nhl3e3a7w {
  stop-color: var(--svg-color--734434, #734434);
}

.o2mxooxqg {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M42.56 37.68c-.16-1.08-2.65-.87-3.9.41c-1.25 1.29-1.12 3.86-.03 3.91c.91.04.77-1.53 1.67-2.44c.9-.89 2.39-.98 2.26-1.88");
}

.pbhk4d3rv {
  d: path("M106.92 95.98h-.16c-.2-.02-7.14-1.06-19.32-4.95c-4.63-1.48-14.35-6.25-20.73-11.17c-6.34-4.88-10.03-9.78-10.19-9.98c-.51-.68-.37-1.64.31-2.15s1.64-.37 2.15.31c.04.05 3.62 4.78 9.6 9.39c5.84 4.5 15.28 9.13 19.86 10.7c10.49 3.61 18.51 4.79 18.55 4.79c.84.07 1.47.81 1.41 1.65c-.05.79-.7 1.39-1.48 1.41");
}

.rj-md3s9a {
  stop-color: var(--svg-color--51362d, #51362d);
}

.rw50bdbub {
  stop-color: var(--svg-color--8a523f, #8a523f);
}

.tes9dgb5h {
  cx: 46.45px;
  cy: 38.13px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  rx: 2.3px;
  ry: 2.75px;
}

.tx_gq1jwb {
  fill: var(--svg-color--cf7756, #cf7756);
  d: path("M105.69 118.48c-.63.08-1.25-.29-1.47-.9l-2.82-7.87c-.26-.72.12-1.51.83-1.77c.72-.26 1.51.12 1.77.83l2.82 7.87c.26.72-.12 1.51-.83 1.77c-.1.04-.2.06-.3.07m13.25-13.24c.08-.63-.29-1.25-.9-1.47l-7.87-2.82c-.72-.26-1.51.12-1.77.83c-.26.72.12 1.51.83 1.77l7.87 2.82c.72.26 1.51-.12 1.77-.83c.03-.11.06-.2.07-.3M42.78 57.91s-5.38-4.9-7.04-9.18c-1.46-3.77-1.8-7.46 2.12-11.32c4.36-4.29 8.78-3.66 13.15-1.61c3.53 1.65 7.98 6 7.98 6z");
}

.ukr4qybxt {
  d: path("M96.93 105.98v-.16c-.02-.2-1.06-7.14-4.95-19.32c-1.48-4.63-6.25-14.35-11.17-20.73c-4.88-6.34-9.78-10.03-9.98-10.19c-.68-.51-1.64-.37-2.15.31s-.37 1.64.31 2.15c.05.04 4.78 3.62 9.39 9.6c4.5 5.84 9.13 15.28 10.7 19.86c3.61 10.49 4.79 18.51 4.79 18.55c.07.84.81 1.47 1.65 1.41c.78-.06 1.39-.71 1.41-1.48");
}

.x0j9b1brc {
  fill: var(--svg-color--cf7756, #cf7756);
  d: path("M59.99 62.34c-5.96-1.32-11.58 1.29-13.94 2.62c5.6 5.02 10.13 3.7 10.13 3.7l6.85-4.3s-1.13-1.59-3.04-2.02m2.81-2.81c-1.32-5.96 1.29-11.58 2.62-13.94c5.02 5.6 3.7 10.13 3.7 10.13l-4.3 6.85c-.01.01-1.6-1.13-2.02-3.04");
}

.ywye0tbyg {
  cx: 38.95px;
  cy: 45.82px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  rx: 2.3px;
  ry: 2.75px;
}

.yz_gy2b2e {
  stop-color: var(--svg-color--c87354, #c87354);
}

</style>
