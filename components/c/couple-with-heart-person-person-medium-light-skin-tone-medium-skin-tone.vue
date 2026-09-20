<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="sp9whbrnm"/><path class="hgq2m1b5m"/><path class="a68olpf0x"/><path class="w_9rcqbey"/><radialGradient id="SVG1W23tbeg" cx="151.397" cy="171.171" r="16.097" gradientTransform="matrix(.9751 .1209 .0577 -.4746 -118.518 166.78)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVG1W23tbeg)" class="nf7iserhf"/><radialGradient id="SVGD70rKc3Y" cx="135.544" cy="168.778" r="4.757" gradientTransform="matrix(-.933 .3 .2276 .6872 142.762 -53.2)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVGD70rKc3Y)" class="yt__dfc8k"/><radialGradient id="SVGJUY1we7F" cx="147.872" cy="155.321" r="20.894" gradientTransform="matrix(.0444 -.9725 -.8177 -.0404 164.73 239.039)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGJUY1we7F)" class="hwgav7zii"/><radialGradient id="SVGpb57WcIj" cx="3.267" cy="155.321" r="20.894" gradientTransform="matrix(.1899 -.9545 .8031 .1606 -107.483 63.864)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGpb57WcIj)" class="ll-zt35sz"/><radialGradient id="SVGfcM9p4EZ" cx="6.792" cy="171.171" r="16.097" gradientTransform="matrix(-.9751 -.1209 .0577 -.4746 16.198 183.482)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGfcM9p4EZ)" class="akcc35s3r"/><radialGradient id="SVG7UQdPdsA" cx="-9.061" cy="168.778" r="4.757" gradientTransform="matrix(.8334 .519 -.3855 .6112 76.892 -1.26)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVG7UQdPdsA)" class="ix_qkfb5h"/><path class="uxx2bu9lh"/><linearGradient id="SVGKvtPqbqW" x1="1211.798" x2="1211.798" y1="123.518" y2="110.865" gradientTransform="matrix(-1 0 0 1 1241.643 0)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ox_82abet"/><stop offset="1" class="b9v4yvbqg"/></linearGradient><path fill="url(#SVGKvtPqbqW)" class="uv46wxxws"/><path class="rfoi1ihhb"/><path class="otbnqpyoj"/><path class="tvq7yek8b"/><g class="qp89kubki"><ellipse transform="rotate(-82.998 19.6 85.319)" class="c6eeicbnq"/><ellipse transform="rotate(-82.998 42.82 88.17)" class="l74z-40vc"/></g><path class="km15rzlwy"/><path class="hf8kbsybg"/><path class="z9cdjmb5n"/><radialGradient id="SVG16ajbc7X" cx="26.305" cy="143.826" r="25.072" gradientTransform="matrix(.1804 .9797 -.7143 .144 142.877 30.558)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVG16ajbc7X)" class="f0f8edc2m"/><radialGradient id="SVGerixQeLL" cx="1.863" cy="116.488" r="6.574" gradientTransform="matrix(.7974 .5715 -.6744 .9711 101.626 -67.112)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="atqdr-9uk"/><stop offset="1" class="l1arbqe-k"/></radialGradient><path fill="url(#SVGerixQeLL)" class="twod4t4kx"/><radialGradient id="SVGyb7ukbaj" cx="289.679" cy="67.953" r="20.208" gradientTransform="matrix(-.8621 -.5006 .2778 -.4987 268.177 239.534)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGyb7ukbaj)" class="bp8xl1cjs"/><radialGradient id="SVG85JWueTe" cx="-.777" cy="122.486" r="6.034" gradientTransform="matrix(.9715 .1166 -.1522 1.2134 40.638 -95.81)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVG85JWueTe)" class="h44e20bef"/><radialGradient id="SVGSxxscets" cx="-1.607" cy="133.136" r="11.316" gradientTransform="matrix(-.9058 -.3704 .3487 -.868 -28.775 178.153)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVGSxxscets)" class="qviygeb9o"/><radialGradient id="SVG3N3ebc8i" cx="-4.291" cy="144.063" r="11.881" gradientTransform="matrix(.9455 .2507 -.3593 1.3585 70.96 -120.92)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="l1arbqe-k"/><stop offset="1" class="atqdr-9uk"/></radialGradient><path fill="url(#SVG3N3ebc8i)" class="mgq-76x1r"/><path class="ki4fo1bur"/><radialGradient id="SVGejS5qe6C" cx="47.61" cy="33.708" r="16.097" gradientTransform="matrix(.9754 -.1186 -.0588 -.4745 63.003 123.07)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGejS5qe6C)" class="rgf2k8o7i"/><radialGradient id="SVGjNaXpdJA" cx="31.756" cy="31.315" r="4.757" gradientTransform="matrix(-.8327 .5168 .3871 .6117 136.954 61.67)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGjNaXpdJA)" class="y4ims1b0k"/><radialGradient id="SVG84BEmdTt" cx="44.085" cy="17.858" r="20.894" gradientTransform="matrix(-.1922 -.9544 -.8032 .1586 131.815 124.942)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVG84BEmdTt)" class="l1lpllbyx"/><radialGradient id="SVGg9oYg8WK" cx="107.054" cy="17.858" r="20.894" gradientTransform="matrix(-.0466 -.9721 .8181 -.0385 72.967 193.666)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGg9oYg8WK)" class="oxkcj15_v"/><radialGradient id="SVG0kyfbVzV" cx="110.58" cy="33.708" r="16.097" gradientTransform="matrix(-.9754 .1186 -.0588 -.4745 197.759 106.683)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVG0kyfbVzV)" class="kn8po_ujb"/><radialGradient id="SVGZxQJ5b5U" cx="94.726" cy="31.315" r="4.757" gradientTransform="matrix(.9342 .302 -.2262 .6863 -9.24 53.28)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVGZxQJ5b5U)" class="ae3kow5dq"/><linearGradient id="SVGFkvz7bfo" x1="98.236" x2="98.236" y1="123.518" y2="110.865" gradientUnits="userSpaceOnUse"><stop offset="0" class="m06zxpakv"/><stop offset="1" class="mujsf_8ht"/></linearGradient><path fill="url(#SVGFkvz7bfo)" class="sf487zrpt"/><path class="une0pze2z"/><path class="jsja6zbkb"/><path class="nscpikwju"/><g class="h3iawzbwl"><ellipse transform="rotate(-7.002 84.138 88.117)" class="en5pq9bli"/><ellipse transform="rotate(-7.002 107.351 85.267)" class="mkctp8lzr"/></g><path class="rzu0jxexu"/><path class="qyx08yblo"/><path class="sak4yrxgq"/><radialGradient id="SVGWzKltFjS" cx="130" cy="10.381" r="25.072" gradientTransform="matrix(.4121 .9069 -.6582 .3126 59.969 -47.15)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGWzKltFjS)" class="xnjmeqjyk"/><radialGradient id="SVG1W3yOczf" cx="105.557" cy="-16.957" r="6.574" gradientTransform="matrix(.912 .3617 -.4195 1.1055 -23.662 30.41)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="no9o3hbeo"/><stop offset="1" class="gjeqb-b1b"/></radialGradient><path fill="url(#SVG1W3yOczf)" class="fd8ri5avf"/><radialGradient id="SVGqmV2dc8n" cx="109.313" cy="29.081" r="20.208" gradientTransform="matrix(-.9575 -.2772 .1489 -.5511 195.744 106.228)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGqmV2dc8n)" class="v5rk5p0bb"/><radialGradient id="SVGmrCr9ccH" cx="102.918" cy="-10.959" r="6.034" gradientTransform="matrix(.9709 -.1219 .1458 1.2142 -20.456 81.964)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGmrCr9ccH)" class="zs53l35su"/><radialGradient id="SVGpZfzTcga" cx="102.088" cy="-.309" r="11.316" gradientTransform="matrix(-.9685 -.1402 .1284 -.9266 177.246 80.815)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGpZfzTcga)" class="x88moacgv"/><radialGradient id="SVGzgJizeCo" cx="99.403" cy="10.618" r="11.881" gradientTransform="matrix(.9781 .0146 -.02 1.4051 -19.984 61.594)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="gjeqb-b1b"/><stop offset="1" class="no9o3hbeo"/></radialGradient><path fill="url(#SVGzgJizeCo)" class="xh5lprb3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:couple-with-heart-person-person-medium-light-skin-tone-medium-skin-tone" /></template>
<style>
.a68olpf0x {
  fill: var(--svg-color--f386ab, #f386ab);
  d: path("M41.4 11.36c1.8-2.25 5.03-4.11 7.76-1.97c1.48 1.16.83 3.54-.49 4.54c-1.93 1.46-3.6 2.34-4.77 4.63c-.7 1.38-1.13 2.88-1.34 4.42c-.08.61-.88.75-1.18.22c-2.04-3.6-2.61-8.55.02-11.84m28.91 4.73c-.85 0-1.44-.82-1.13-1.61a19.3 19.3 0 0 1 2.2-4.11c1.32-1.85 3.82-2.92 5.41-1.81c1.63 1.15 1.42 3.43.27 4.54c-2.45 2.39-5.53 2.99-6.75 2.99");
}

.ae3kow5dq {
  d: path("M76.93 105.82c2.34-4.66-4.23-5.5-4.23-5.5l-.01.01c1.28 1.23 1.93 2.35 1.42 3.61c-.62 1.56-3.01 2.06-3.01 2.06s3.65 2.5 5.83-.18");
}

.akcc35s3r {
  d: path("m28.13 111.7l.76-6.27l-18.97-3.88l-2 1.91s3.44 6.16 14.21 7.5z");
}

.atqdr-9uk {
  stop-color: var(--svg-color--bfa055, #bfa055);
}

.b9v4yvbqg {
  stop-color: var(--svg-color--67b730, #67b730);
}

.bp8xl1cjs {
  d: path("M46.23 50.58c4.83 1.98 6.94 4.88 7.32 8.45c.11 1.05-.8 10.59-17.21-2.35c-6.11-4.81-3.99-7.11-3.18-7.3c3.16-.76 7.66-1.02 13.07 1.2");
}

.c6eeicbnq {
  cx: 19.6px;
  cy: 85.32px;
  rx: 3.63px;
  ry: 3.51px;
}

.en5pq9bli {
  cx: 84.16px;
  cy: 88.14px;
  rx: 3.51px;
  ry: 3.63px;
}

.f0f8edc2m {
  d: path("M56.24 87.23c.25-1.07 3.28-2.16 5.09-6.66c.19-.48.37-.97.53-1.46c1.71-5.53.56-10.93-.33-12.77c-1.24-2.57-4.16-6.09-7.22-7.11q-.405-.105-.78-.18s.04 1.52-.71 2.65c-.96 1.46-2.57 1.64-2.57 1.64c7.14 9.33 5.68 16.26 5.99 23.89");
}

.fd8ri5avf {
  d: path("M86.59 51.24c-.7.46-1.32.91-1.85 1.3c-.61.45-4.56 3.38-7.74 2.03c-1.95-.83-2.29-3.67-2.3-3.77c-.71 1.2-2.31 9.35 5.18 8.94c3.23-.18 4.86-3.28 5.74-5.85c.32-.92.83-2.28.97-2.65");
}

.gjeqb-b1b {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
  stop-opacity: 0;
}

.h3iawzbwl {
  fill: var(--svg-color--49362e, #49362e);
}

.h44e20bef {
  d: path("M19.42 46.8c-.01 0-.02.01-.04.01c-.67.2-5.97 1.96-4.84 8.1l5.21 1.51c-4.1-5.44-.3-9.63-.3-9.63s-.02.01-.03.01");
}

.hf8kbsybg {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M33.13 93.61a1 1 0 0 0-.22-.09l-5-.61c-.08 0-.16.01-.23.03c-.48.13-.78.57-.63 1.09c.15.53.97 2.05 2.98 2.3s3.17-1.03 3.45-1.51c.27-.47.08-.97-.35-1.21");
}

.hgq2m1b5m {
  fill: var(--svg-color--da2e75, #da2e75);
  d: path("M47.94 4.81c8.27 0 12.38 8.89 13.71 12.5c.19.51.91.53 1.12.03l1.21-2.83c-1.71-5.45-6.4-10.77-14.41-10.77c-3.32 0-6.82 1.1-9.55 3.41c2.4-1.59 5.23-2.34 7.92-2.34m30.47-1.07c-2.55 0-4.7.74-6.51 1.85c1.27-.49 2.68-.78 4.23-.78c7.8 0 14.77 5.91 11.62 19.58c-2.7 11.73-18.5 25.96-23.32 31.39c-.31.35-.41.91-.41.91s24.72-17.9 28.08-32.26c3.36-14.37-5.72-20.69-13.69-20.69");
}

.hwgav7zii {
  d: path("M60.64 82.6c2.01 7.23-1.85 13.94-5.02 16.57c-.44.36-2.26 1.75-2.79 2.97c0 0-5.32-9.63-6.6-15.06c-.26-1.1-.48-2.22-.39-3.34c.07-.84.32-1.82.89-2.47c.7-.8 13.65.55 13.65.55c.01.01.26.78.26.78");
}

.ix_qkfb5h {
  d: path("M8.3 100.72c3.4-3.96-2.77-6.36-2.77-6.36h-.01c.94 1.5 1.3 2.75.51 3.84c-.99 1.37-3.43 1.28-3.43 1.28s2.94 3.31 5.7 1.24");
}

.jsja6zbkb {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M91.67 53.24c-12.19 1.5-21.88 15.92-19.57 34.68c2.29 18.66 15.05 26.45 26.9 25s22.34-12.11 20.05-30.77c-2.31-18.75-15.2-30.4-27.38-28.91");
}

.ki4fo1bur {
  fill: var(--svg-color--543930, #543930);
  d: path("M120.89 98.25c-1.02-1.41-.15-3.07 1.44-5.19c2.51-3.37 4.79-10.74.99-17.48c.01-.04-.73-1.17-.72-1.21l-1.21.09c-.39-.01-13.59 1.57-26.81 3.18c-13.21 1.61-26.41 3.24-26.79 3.34c0 0-1.62 1.51-1.6 1.55c-2.04 7.45 1.97 14.06 5.23 16.72c2.05 1.68 3.31 3.08 2.66 4.69c-.63 1.56-3.02 2.07-3.02 2.07s.74 1.43 2.19 2.08c1.34.6 2.88.59 3.94.48c0 0 4.82 5.15 15.6 3.84l6-.73l6-.73c10.78-1.31 14.2-7.46 14.2-7.46c1.05-.15 2.56-.51 3.71-1.41c1.24-.97 1.61-2.54 1.61-2.54s-2.43.07-3.42-1.29");
}

.km15rzlwy {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M35.65 99.71c-2.41 1.06-9.79.16-11.88-1.46c-1.2-.93-2.66.09-2.27 1.33c.39 1.22 4.08 4.39 7.56 4.82s7.78-1.76 8.45-2.85c.69-1.11-.47-2.44-1.86-1.84");
}

.kn8po_ujb {
  d: path("m98.83 111.67l-.78-6.27l-19.34.83l-1.48 2.33s4.82 5.15 15.6 3.84z");
}

.l1arbqe-k {
  stop-color: var(--svg-color--bfa055, #bfa055);
  stop-opacity: 0;
}

.l1lpllbyx {
  d: path("M123.33 75.57c3.7 6.53 1.58 13.97-.86 17.29c-.33.46-1.77 2.24-1.99 3.56c0 0-7.49-8.06-10.05-13.02c-.52-1-1-2.04-1.19-3.15c-.14-.83-.13-1.84.27-2.61c.49-.94 13.38-2.77 13.38-2.77c.01.02.44.7.44.7");
}

.l74z-40vc {
  cx: 42.82px;
  cy: 88.17px;
  rx: 3.63px;
  ry: 3.51px;
}

.ll-zt35sz {
  d: path("M3.53 75.52c-3.68 6.52-1.55 13.97.9 17.31c.34.46 1.77 2.25 1.99 3.57c0 0 7.47-8.04 10.01-13c.51-1 1-2.04 1.18-3.15c.14-.83.13-1.84-.27-2.61c-.49-.95-1.21-.8-2.23-.92c-1.93-.24-10.32-1.78-10.98-1.86z");
}

.m06zxpakv {
  stop-color: var(--svg-color--ed6d23, #ed6d23);
}

.mgq-76x1r {
  d: path("M6.32 65.7c-1.8 1.27-4.4 4.28-3.3 8.54C3.85 77.45 8 79.29 8 79.29c0 .01.83.38 1.27.43l2.93-15.16c-2.07-.25-4.14.15-5.54.91c.01.03-.35.21-.34.23");
}

.mkctp8lzr {
  cx: 107.38px;
  cy: 85.29px;
  rx: 3.51px;
  ry: 3.63px;
}

.mujsf_8ht {
  stop-color: var(--svg-color--f78c1f, #f78c1f);
}

.nf7iserhf {
  d: path("m28.1 111.69l.76-6.27l19.33.87l1.48 2.34s-4.81 5.14-15.58 3.81z");
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.nscpikwju {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M88.49 81.16c-.76-.79-2.43-1.86-5.37-1.5s-4.3 1.81-4.85 2.76c-.24.42-.11.85.12 1.1c.22.23.79.39 1.38.11c.58-.28 1.69-1.04 3.68-1.3c1.99-.23 3.25.24 3.88.37s1.15-.17 1.31-.44c.17-.3.19-.75-.15-1.1m23.22-2.85c-.76-.79-2.43-1.86-5.37-1.5s-4.3 1.81-4.85 2.76c-.24.42-.11.85.12 1.1c.22.23.79.39 1.38.11c.58-.28 1.69-1.04 3.68-1.3c1.99-.23 3.25.24 3.88.37s1.15-.17 1.31-.44c.17-.3.19-.75-.15-1.1");
}

.otbnqpyoj {
  fill: var(--svg-color--e0bb95, #e0bb95);
  d: path("M35.32 53.27c-12.19-1.5-25.08 10.15-27.38 28.91c-2.29 18.66 8.21 29.31 20.05 30.77s24.61-6.34 26.9-25c2.31-18.76-7.38-33.18-19.57-34.68");
}

.ox_82abet {
  stop-color: var(--svg-color--4d7d23, #4d7d23);
}

.oxkcj15_v {
  d: path("M66.2 82.52c-1.99 7.22 1.88 13.93 5.06 16.58c.44.36 2.27 1.75 2.8 2.98c0 0 5.3-9.61 6.57-15.04c.26-1.1.47-2.22.38-3.34c-.07-.84-.32-1.82-.9-2.47c-.7-.8-1.37-.48-2.38-.36c-1.93.23-10.44.77-11.1.85c0 .01-.43.8-.43.8");
}

.qp89kubki {
  fill: var(--svg-color--5d4037, #5d4037);
}

.qviygeb9o {
  d: path("m17.75 55.85l-3.22-.94c-.13-.02-.57-.03-.81-.02c-1.88.04-4.19.76-5.68 3.12c-1.61 2.54-1.86 4.86-1.71 6.44c.03.53.17 1.14.17 1.14s1.83-1.38 5.71-1.02z");
}

.qyx08yblo {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M99.3 92.91a1 1 0 0 0-.23-.03l-5 .61c-.08.02-.15.05-.22.09c-.43.24-.62.74-.35 1.21c.28.47 1.44 1.75 3.45 1.51c2.01-.25 2.83-1.77 2.98-2.3c.15-.52-.15-.96-.63-1.09");
}

.rfoi1ihhb {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("M29.61 117.83a6.8 6.8 0 0 1-6.8-6.8v-4.54h13.61v4.54a6.816 6.816 0 0 1-6.81 6.8");
}

.rgf2k8o7i {
  d: path("m98.8 111.68l-.78-6.27l18.97-3.83l2.01 1.91s-3.42 6.15-14.2 7.46z");
}

.rzu0jxexu {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M103.22 98.23c-2.09 1.61-9.46 2.52-11.88 1.46c-1.39-.61-2.56.73-1.88 1.84c.67 1.09 5.02 3.27 8.5 2.85s7.12-3.59 7.51-4.81c.4-1.25-1.05-2.27-2.25-1.34");
}

.sak4yrxgq {
  fill: var(--svg-color--543930, #543930);
  d: path("M120.27 59.57c-1.98-2.37-6.13-5.36-9.51-5.16c-.93-3.23-4.72-5.59-8.19-6.25c-9.39-1.79-14.88 2.23-17.83 4.39c-.61.45-4.56 3.38-7.74 2.03c-1.99-.85-2.31-3.78-2.31-3.78s-5.55 3-2.8 9.07c-1.99.34-4.51 1.53-5.56 4.57c-1.24 3.63-.31 6.41.33 7.72c-1.54 1.71-3.33 5.16-1.35 9.1c1.49 2.97 6.13 3.84 6.13 3.84c.36 5.63 1.49 9.07 2.19 10.39c.12.23.46.17.49-.09c.34-2.85 1.79-12.92 1.36-14.57c0 0 7.56-2.54 14.29-9.04c1.37-1.32 2.88-2.49 4.53-3.42c8.83-4.94 11.55 1.26 11.55 1.26s6.28-2.07 9.32 6.82c1.14 3.33 2.91 8.57 3.78 12.36c.06.27.43.28.5.02c.47-1.6.79-4.61.73-7.72c-.02-1.1 2.66-2.89 3.33-7.69c.92-6.42-1.81-12.13-3.24-13.85");
}

.sf487zrpt {
  d: path("M102 111.11h-7.52c-8.7-.66-21.57 3.25-24.48 12.89h56.46c-2.89-9.64-15.77-13.55-24.46-12.89");
}

.sp9whbrnm {
  fill: var(--svg-color--ef5592, #ef5592);
  d: path("M78.41 3.74C67.87 3.74 64 14.5 64 14.5S60.18 3.74 49.57 3.74c-7.97 0-17.07 6.32-13.71 20.68s28.16 32.26 28.16 32.26s24.72-17.9 28.08-32.26S87.02 3.74 78.41 3.74");
}

.tvq7yek8b {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M25.49 79.59c-.55-.95-1.91-2.4-4.85-2.76s-4.61.71-5.37 1.5a.9.9 0 0 0-.15 1.09c.16.27.68.57 1.31.44s1.89-.6 3.88-.37c1.99.26 3.1 1.02 3.68 1.3s1.16.12 1.38-.11a.91.91 0 0 0 .12-1.09m23.22 2.85c-.55-.95-1.91-2.4-4.85-2.76s-4.61.71-5.37 1.5a.9.9 0 0 0-.15 1.09c.16.27.68.57 1.31.44s1.89-.6 3.88-.37c1.99.26 3.1 1.02 3.68 1.3s1.16.12 1.38-.11c.23-.23.36-.67.12-1.09");
}

.twod4t4kx {
  d: path("M30.88 50.1c-.8.28-1.5.57-2.11.82c-.7.29-5.25 2.18-8 .1c-1.69-1.28-1.34-4.11-1.32-4.21c-.98.99-4.5 8.51 2.87 9.93c3.18.61 5.51-2.01 6.99-4.29c.52-.83 1.35-2.03 1.57-2.35");
}

.une0pze2z {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M98 117.83a6.8 6.8 0 0 1-6.8-6.8v-4.54h13.61v4.54a6.816 6.816 0 0 1-6.81 6.8m16.19-39.36l-38.28 4.7c-4.13.51-7.06 4.52-6.52 8.91c.54 4.4 4.36 7.58 8.49 7.07l38.28-4.7c4.13-.51 7.06-4.52 6.52-8.91c-.54-4.4-4.36-7.58-8.49-7.07");
}

.uv46wxxws {
  d: path("M26.08 111.11h7.52c8.69-.66 21.56 3.24 24.47 12.89H1.61c2.91-9.64 15.78-13.55 24.47-12.89");
}

.uxx2bu9lh {
  fill: var(--svg-color--c48e6a, #c48e6a);
  d: path("m51.07 83.19l-38.28-4.7c-4.13-.51-7.95 2.68-8.49 7.07s2.4 8.41 6.52 8.91l38.28 4.7c4.13.51 7.95-2.68 8.49-7.07s-2.39-8.4-6.52-8.91");
}

.v5rk5p0bb {
  d: path("M101.6 47.99c5.17.76 7.92 3.05 9.15 6.42c.36.99 1.79 10.47-17.27 1.89c-7.09-3.19-5.59-5.94-4.85-6.32c2.89-1.49 7.18-2.83 12.97-1.99");
}

.w_9rcqbey {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M52.79 104.01c-.65-1.61.6-3.01 2.65-4.69c3.25-2.66 7.25-9.26 5.19-16.72c.02-.04-.42-1.31-.4-1.34l-1.2-.21c-.38-.1-13.57-1.77-26.78-3.4C19.04 76 5.84 74.39 5.45 74.4c0 0-1.94 1.07-1.92 1.12c-3.78 6.74-1.49 14.12 1.03 17.49c1.59 2.12 2.47 3.79 1.45 5.2c-.99 1.37-3.43 1.28-3.43 1.28s.37 1.57 1.62 2.54c1.15.9 2.66 1.27 3.71 1.42c0 0 3.44 6.16 14.21 7.5l6 .74l6 .75c10.77 1.34 15.58-3.81 15.58-3.81c1.06.11 2.6.12 3.94-.47c1.44-.64 2.18-2.07 2.18-2.07s-2.4-.52-3.03-2.08");
}

.x88moacgv {
  d: path("m75.24 60l-3.35-.13c-.13.02-.56.11-.8.18c-1.82.5-3.88 1.75-4.76 4.4c-.95 2.85-.63 5.16-.1 6.66c.16.51.44 1.06.44 1.06s1.44-1.78 5.3-2.37z");
}

.xh5lprb3w {
  d: path("M66.53 72.32c-1.44 1.67-3.23 5.22-1.13 9.08c1.58 2.91 6.06 3.7 6.06 3.7c0 .01.9.17 1.34.11l-.83-15.41c-2.07.26-3.98 1.14-5.15 2.22c.01.02-.3.28-.29.3");
}

.xnjmeqjyk {
  d: path("M120.18 81.13c-.02-1.1 2.66-2.89 3.33-7.69c.07-.51.12-1.03.16-1.55c.32-5.78-2.1-10.74-3.41-12.31c-1.83-2.19-5.51-4.9-8.73-5.15c-.28 0-.55 0-.8.01c0 0 .4 1.47-.05 2.74c-.58 1.65-2.1 2.21-2.1 2.21c9.2 7.34 9.45 14.41 11.6 21.74");
}

.y4ims1b0k {
  d: path("M118.61 100.75c-3.41-3.97 2.76-6.35 2.76-6.35h.01c-.94 1.5-1.29 2.75-.5 3.84c.99 1.37 3.43 1.29 3.43 1.29s-2.93 3.3-5.7 1.22");
}

.yt__dfc8k {
  d: path("M49.97 105.89c-2.35-4.67 4.22-5.49 4.22-5.49l.01.01c-1.27 1.23-1.92 2.35-1.41 3.6c.63 1.57 3.02 2.08 3.02 2.08s-3.65 2.48-5.84-.2");
}

.z9cdjmb5n {
  fill: var(--svg-color--ab872f, #ab872f);
  d: path("M61.54 66.33c-1.35-2.78-4.65-6.68-7.98-7.31c-.12-3.36-3.23-6.56-6.44-8.05c-8.68-4.01-14.97-1.44-18.36-.06c-.7.29-5.25 2.18-8 .1c-1.72-1.3-1.32-4.22-1.32-4.22s-6.11 1.57-4.91 8.12c-2.01-.16-4.75.39-6.5 3.09c-2.08 3.22-1.85 6.15-1.55 7.57c-1.91 1.28-4.48 4.2-3.51 8.51C3.71 77.33 8 79.29 8 79.29c-1.02 5.55-.75 9.16-.38 10.61c.06.25.41.27.5.03c1.02-2.69 4.87-12.1 4.85-13.81c0 0 7.95-.64 16.05-5.31c1.65-.95 3.4-1.72 5.22-2.22c9.76-2.66 10.9 4.01 10.9 4.01s6.6-.49 7.4 8.87c.3 3.51.75 9.02.68 12.9c0 .27.35.37.49.14c.84-1.44 1.88-4.28 2.58-7.32c.25-1.07 3.28-2.16 5.09-6.66c2.4-5.99 1.13-12.19.16-14.2");
}

.zs53l35su {
  d: path("M74.68 50.81c-.01.01-.02.01-.04.02c-.6.35-5.32 3.34-2.74 9.03l5.42.21c-5.29-4.29-2.62-9.28-2.62-9.28z");
}

</style>
