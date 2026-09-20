<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<radialGradient id="SVGo4IBudBI" cx="64.139" cy="4.464" r="69.458" gradientTransform="matrix(-1.08 .0045 .0029 .5843 133.401 120.64)" gradientUnits="userSpaceOnUse"><stop offset=".559" class="sl8ua6bht"/><stop offset="1" class="l_ukgm8gc"/></radialGradient><path fill="url(#SVGo4IBudBI)" class="atoxhkjhq"/><path class="g97x0nbuz"/><radialGradient id="SVGgsYncbxx" cx="99.638" cy="45.85" r="23.419" gradientTransform="matrix(1 0 0 .4912 -21.055 59.629)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGgsYncbxx)" class="w3bjiqbbq"/><radialGradient id="SVGFgFbwc5w" cx="76.573" cy="49.332" r="6.921" gradientTransform="rotate(154.924 84.432 60.42)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVGFgFbwc5w)" class="erztp3bup"/><radialGradient id="SVGdXOaYcRr" cx="94.509" cy="68.91" r="30.399" gradientTransform="matrix(-.0746 -.9972 .8311 -.0622 33.494 157.622)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGdXOaYcRr)" class="xk9q3hbtw"/><radialGradient id="SVG7bKMSdlo" cx="44.31" cy="68.91" r="30.399" gradientTransform="matrix(.0746 -.9972 -.8311 -.0622 98.274 107.563)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVG7bKMSdlo)" class="pljcr_pki"/><radialGradient id="SVGPKzcDbDz" cx="49.439" cy="45.85" r="23.419" gradientTransform="matrix(-1 0 0 .4912 98.878 59.629)" gradientUnits="userSpaceOnUse"><stop offset=".728" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGPKzcDbDz)" class="tmdmorb6l"/><radialGradient id="SVGFrheaeaw" cx="26.374" cy="49.332" r="6.921" gradientTransform="rotate(205.076 4.678 51.766)scale(-1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVGFrheaeaw)" class="aajsnwbfh"/><path class="u-nlmubgv"/><path class="edh-k8aeq"/><linearGradient id="SVGqERK7dSC" x1="26.655" x2="26.655" y1="11.255" y2="31.458" gradientTransform="matrix(-1 0 0 -1 104.157 128)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ohm06yblq"/><stop offset=".668" class="nmuty9thj"/><stop offset=".987" class="ip0ngccya"/></linearGradient><path fill="url(#SVGqERK7dSC)" class="j0fsbf1vm"/><linearGradient id="SVGmjQXCSPJ" x1="12.773" x2="12.773" y1="11.255" y2="31.458" gradientTransform="matrix(1 0 0 -1 37.757 128)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="ohm06yblq"/><stop offset=".668" class="nmuty9thj"/><stop offset=".987" class="ip0ngccya"/></linearGradient><path fill="url(#SVGmjQXCSPJ)" class="fhy9tyb8v"/><path class="bqgcswoxb"/><linearGradient id="SVGFlKgreMo" x1="34.007" x2="24.6" y1="23.511" y2="12.679" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vlzxxcccm"/><stop offset="1"/></linearGradient><path fill="url(#SVGFlKgreMo)" class="dcvsc8mni"/><linearGradient id="SVGnz6XNdNz" x1="42.813" x2="33.406" y1="15.863" y2="5.032" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vlzxxcccm"/><stop offset="1"/></linearGradient><path fill="url(#SVGnz6XNdNz)" class="w3dtcf9mi"/><path class="g_21fnbpp"/><linearGradient id="SVGmf4O0dRR" x1="87.856" x2="93.231" y1="18.892" y2="7.517" gradientTransform="matrix(1 0 0 -1 0 128)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vlzxxcccm"/><stop offset="1"/></linearGradient><circle fill="url(#SVGmf4O0dRR)" class="wnupkvb4r"/><circle class="g_v2gpbya"/><path class="k0f8q8b4s"/><path class="wh3ux7ahc"/><path class="hbr9c9b-f"/><g class="fgqj36-ft"><ellipse class="xm_cxnkcf"/><ellipse class="qi4mcqr9e"/></g><path class="bweq3i9ef"/><path class="l9f7edb5l"/><path class="xi7vbwb8n"/><radialGradient id="SVGLTwW1bea" cx="82.019" cy="84.946" r="35.633" gradientTransform="matrix(.3076 .9515 .706 -.2282 -3.184 -15.605)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGLTwW1bea)" class="z0wnxiz1y"/><radialGradient id="SVGv7WBHb4V" cx="47.28" cy="123.8" r="9.343" gradientTransform="matrix(.8813 .4726 .5603 -1.045 -63.752 111.228)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="m_5onzv2u"/><stop offset="1" class="mlb8vsb9l"/></radialGradient><path fill="url(#SVGv7WBHb4V)" class="b36gj8bmp"/><radialGradient id="SVGee9UheBQ" cx="159.055" cy="62.862" r="28.721" gradientTransform="matrix(-.9378 -.3944 -.2182 .5285 231.04 50.678)" gradientUnits="userSpaceOnUse"><stop offset=".699" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGee9UheBQ)" class="m1-eewucy"/><radialGradient id="SVGlS6gJb0L" cx="43.529" cy="115.276" r="8.575" gradientTransform="matrix(1 0 0 -1.2233 0 153.742)" gradientUnits="userSpaceOnUse"><stop offset=".702" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGlS6gJb0L)" class="v16xqhb_x"/><radialGradient id="SVGoeYcZcVK" cx="42.349" cy="100.139" r="16.083" gradientTransform="matrix(-.9657 -.2598 -.2432 .9037 107.598 -51.632)" gradientUnits="userSpaceOnUse"><stop offset=".66" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGoeYcZcVK)" class="gtqbt9beb"/><radialGradient id="SVGua8NcbaY" cx="38.533" cy="84.609" r="16.886" gradientTransform="rotate(187.833 -2.584 78.504)scale(-1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="mlb8vsb9l"/><stop offset="1" class="m_5onzv2u"/></radialGradient><path fill="url(#SVGua8NcbaY)" class="o5ppj9ujw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:health-worker-medium-dark-skin-tone" /></template>
<style>
.aajsnwbfh {
  d: path("M32.92 83.16c4.28-6.5-5.21-8.93-5.21-8.93l-.01.01c1.65 2.05 2.4 3.84 1.43 5.61c-1.21 2.21-4.81 2.53-4.81 2.53s4.91 4.36 8.6.78");
}

.atoxhkjhq {
  d: path("M64.03 95.93c-25.51.07-51.97 7.33-51.97 25.06v3.04H116v-3.04c0-17.74-26.46-25-51.97-25.06");
}

.b36gj8bmp {
  d: path("M56.95 7.39c-1.1.53-2.06 1.06-2.9 1.51c-.96.52-7.17 3.97-11.51 1.5c-2.67-1.52-2.67-5.58-2.67-5.72c-1.23 1.57-4.95 12.78 5.93 13.53c4.69.32 7.58-3.77 9.3-7.23c.62-1.26 1.59-3.1 1.85-3.59");
}

.bqgcswoxb {
  fill: none;
  stroke: var(--svg-color--03a9f4, #03a9f4);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("M32.94 104.33c1.57-.82 3.4-2.02 4.25-2.76c1.92-1.67 6.47-5.97 9.86-2.94c3.66 3.21-.1 8.27-1.55 10.37c-.72 1.05-1.27 2.21-1.72 3.39");
}

.bweq3i9ef {
  fill: var(--svg-color--473530, #473530);
  d: path("M72.42 76.14c-3.18 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.44 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.66-1.09-3.33-2.92-2.24");
}

.dcvsc8mni {
  d: path("M29.79 111.35c-.49.08-1.02.29-1.54-.21c-.34-.33-.77-1.27-.65-2.08c.12-.82 1.03-1.16 2.97-1.99c1.51-.64 2.9-1.29 4.16-2.14l-1.88-2.34s-2.17 1.22-3.35 1.68c-2.09.8-4.47 1.71-4.86 4.35c-.42 2.84 1.14 4.86 2.34 5.77c.98.75 1.92 1.11 2.83 1.17c1.41.09 2.35-.83 2.35-2.25s-1.39-2.12-2.37-1.96");
}

.edh-k8aeq {
  fill: var(--svg-color--81d4fa, #81d4fa);
  d: path("m52.66 102l3.85 22H71.9l3.44-22z");
}

.erztp3bup {
  d: path("M95.1 83.16c-4.28-6.5 5.21-8.93 5.21-8.93l.01.01c-1.65 2.05-2.4 3.84-1.43 5.61c1.21 2.21 4.81 2.53 4.81 2.53s-4.91 4.36-8.6.78");
}

.fgqj36-ft {
  fill: var(--svg-color--42312c, #42312c);
}

.fhy9tyb8v {
  d: path("M54.91 96.17c-5.92.43-8.69.94-8.69.94l-3.13 7.3l5.25 4.39l-2.83 6.17l5.58 8.99h6.87z");
}

.g_21fnbpp {
  fill: var(--svg-color--03a9f4, #03a9f4);
  d: path("M55.1 93.75c-4.63.09-7.93 2.45-9.19 3.91l2.27 1.96c.03-.03 2.45-2.74 6.92-2.86zm31.16 8.73c-2.43-5.47-6.19-7.55-8.21-8.3c-1.85-.69-3.65-.97-4.97-1.08v3.01c1.08.1 2.49.34 3.93.88c1.58.59 4.53 2.24 6.51 6.71c2.78 6.26 3.48 7.89 3.49 7.89l2.75-1.19s-.7-1.62-3.5-7.92");
}

.g_v2gpbya {
  cx: 90.2px;
  cy: 114.06px;
  r: 4px;
  fill: var(--svg-color--9e9e9e, #9e9e9e);
}

.g97x0nbuz {
  fill: var(--svg-color--3c2c23, #3c2c23);
  d: path("M98.9 79.85c-1.25-2.27.34-4.58 3.06-7.44c4.31-4.54 9-15.07 4.64-25.76c.03-.06-.86-1.86-.83-1.92l-1.79-.09c-.57-.08-20.26-.12-39.97-.12s-39.4.04-39.97.12c0 0-2.65 1.95-2.63 2.01c-4.35 10.69.33 21.21 4.64 25.76c2.71 2.86 4.3 5.17 3.06 7.44c-1.21 2.21-4.81 2.53-4.81 2.53s.83 2.26 2.83 3.48c1.85 1.13 4.13 1.39 5.7 1.43c0 0 6.15 8.51 22.23 8.51h17.9c16.08 0 22.23-8.51 22.23-8.51c1.57-.04 3.85-.3 5.7-1.43c2-1.22 2.83-3.48 2.83-3.48s-3.61-.32-4.82-2.53");
}

.gtqbt9beb {
  d: path("m39.07 17.73l-4.81-.77c-.19 0-.83.06-1.18.11c-2.71.38-5.9 1.78-7.63 5.36c-1.86 3.86-1.81 7.17-1.3 9.38c.15.74.45 1.58.45 1.58s2.38-2.26 8.05-2.41z");
}

.hbr9c9b-f {
  fill: var(--svg-color--42312c, #42312c);
  d: path("M54.8 49.82c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55m32.87 0c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.28-.38.39-1.01-.02-1.55");
}

.ip0ngccya {
  stop-color: var(--svg-color--bdbdbd, #bdbdbd);
}

.j0fsbf1vm {
  d: path("M73.12 96.17c5.92.43 8.69.94 8.69.94l3.13 7.3l-5.25 4.39l2.83 6.17l-5.58 8.99h-6.87z");
}

.k0f8q8b4s {
  fill: var(--svg-color--7a4c32, #7a4c32);
  d: path("M91.33 50.43H36.67c-5.89 0-10.71 5.14-10.71 11.41s4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41s-4.81-11.41-10.7-11.41");
}

.l_ukgm8gc {
  stop-color: var(--svg-color--c6c6c6, #c6c6c6);
}

.l9f7edb5l {
  fill: var(--svg-color--875334, #875334);
  d: path("M67.86 68.06c-.11-.04-.21-.07-.32-.08h-7.08c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.3-.71-.05-1.37-.69-1.63");
}

.m_5onzv2u {
  stop-color: var(--svg-color--554138, #554138);
}

.m1-eewucy {
  d: path("M79.16 5.47c7.32 1.98 10.89 5.71 12.08 10.68c.35 1.46.77 15.08-25.23-.4c-9.67-5.76-7.03-9.36-5.9-9.77c4.42-1.6 10.85-2.73 19.05-.51");
}

.mlb8vsb9l {
  stop-color: var(--svg-color--554138, #554138);
  stop-opacity: 0;
}

.nmuty9thj {
  stop-color: var(--svg-color--d0d0d0, #d0d0d0);
}

.o5ppj9ujw {
  d: path("M24.37 33.58c-2.37 2.1-5.56 6.79-3.21 12.61c1.77 4.39 8.09 6.29 8.09 6.29c0 .02 1.26.4 1.91.4l1.48-21.9c-3.03 0-5.94.91-7.82 2.22c.03.03-.46.35-.45.38");
}

.ohm06yblq {
  stop-color: var(--svg-color--e0e0e0, #e0e0e0);
}

.pljcr_pki {
  d: path("M21.4 46.65c-4.24 10.35.23 21.01 4.41 25.5c.58.62 3.01 3.01 3.57 4.92c0 0 9.54-13.31 12.39-21.13c.58-1.58 1.1-3.2 1.17-4.88c.05-1.26-.14-2.76-.87-3.83c-.89-1.31-1.93-.96-3.44-.96c-2.88 0-15.49-.74-16.47-.74c.01.02-.76 1.12-.76 1.12");
}

.qi4mcqr9e {
  cx: 80.44px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.sl8ua6bht {
  stop-color: var(--svg-color--f5f5f5, #f5f5f5);
}

.tmdmorb6l {
  d: path("M64.03 95.79v-9.44l-28.57-2.26l-2.6 3.2s6.15 8.51 22.23 8.51z");
}

.u-nlmubgv {
  fill: var(--svg-color--7a4c32, #7a4c32);
  d: path("M54.92 90.08v20.96c0 5.26 3.7 9.53 8.26 9.53h1.65c4.56 0 8.26-4.26 8.26-9.53V90.08z");
}

.v16xqhb_x {
  d: path("M39.84 4.68c-.01.01-.03.01-.06.03h-.01c-.93.39-8.24 3.78-5.51 12.25l7.78 1.25c-6.89-6.98-2.17-13.55-2.17-13.55s-.02.01-.03.02");
}

.vlzxxcccm {
  stop-color: var(--svg-color--757575, #757575);
}

.w3bjiqbbq {
  d: path("M63.99 95.79v-9.44l28.57-2.26l2.6 3.2s-6.15 8.51-22.23 8.51z");
}

.w3dtcf9mi {
  d: path("M37.03 116.79c-.01.5-.14 1.05.43 1.49c.38.29 1.37.58 2.15.35c.79-.24 1-1.18 1.54-3.22c.42-1.58.86-3.06 1.52-4.43l2.58 1.52s-.9 2.32-1.18 3.56c-.49 2.19-1.05 4.67-3.61 5.43c-2.75.83-4.98-.44-6.05-1.49c-.88-.87-1.37-1.74-1.56-2.64c-.29-1.38.49-2.45 1.89-2.65s2.31 1.08 2.29 2.08");
}

.wh3ux7ahc {
  fill: var(--svg-color--a56c43, #a56c43);
  d: path("M64 11.07c-17.4 0-33.52 18.61-33.52 45.4c0 26.64 16.61 39.81 33.52 39.81S97.52 83.1 97.52 56.46c0-26.78-16.12-45.39-33.52-45.39");
}

.wnupkvb4r {
  cx: 90.2px;
  cy: 114.06px;
  r: 7px;
}

.xi7vbwb8n {
  fill: var(--svg-color--3c2c23, #3c2c23);
  d: path("M104.07 25.11c-2.44-3.69-7.91-8.64-12.82-8.97c-.79-4.72-5.84-8.72-10.73-10.27c-13.23-4.19-21.84.51-26.46 3.03c-.96.52-7.17 3.97-11.51 1.5c-2.72-1.55-2.67-5.74-2.67-5.74s-8.52 3.25-5.61 12.3c-2.93.12-6.77 1.36-8.8 5.47c-2.42 4.9-1.56 8.99-.86 10.95c-2.52 2.14-5.69 6.69-3.52 12.6c1.64 4.45 8.17 6.5 8.17 6.5c-.46 8.01 1.03 12.94 1.82 14.93c.14.35.63.32.72-.04c.99-3.97 4.37-17.8 4.03-20.21c0 0 11.35-2.25 22.17-10.22c2.2-1.62 4.59-3 7.13-4.01c13.59-5.41 16.43 3.82 16.43 3.82s9.42-1.81 12.26 11.27c1.07 4.9 1.79 12.75 2.4 18.24c.04.39.57.47.72.11c.95-2.18 2.85-6.5 3.3-10.91c.16-1.55 4.34-3.6 6.14-10.26c2.41-8.88-.54-17.42-2.31-20.09");
}

.xk9q3hbtw {
  d: path("M106.62 46.65c4.25 10.35-.22 21.01-4.41 25.51c-.57.62-3.01 3.01-3.57 4.92c0 0-9.54-13.31-12.39-21.13c-.57-1.58-1.1-3.2-1.17-4.88c-.05-1.26.14-2.76.87-3.83c.89-1.31 20.16-1.7 20.16-1.7c0 .01.51 1.11.51 1.11");
}

.xm_cxnkcf {
  cx: 47.56px;
  cy: 58.81px;
  rx: 4.93px;
  ry: 5.1px;
}

.z0wnxiz1y {
  d: path("M100.22 55.5c.16-1.55 4.34-3.6 6.14-10.26c.19-.71.35-1.43.5-2.15c1.46-8.09-1.16-15.52-2.79-17.98c-2.26-3.41-7.1-7.89-11.69-8.81c-.4-.05-.79-.1-1.16-.12c0 0 .33 2.15-.54 3.86c-1.12 2.22-3.41 2.75-3.41 2.75c11.97 11.98 11.12 22 12.95 32.71");
}

</style>
