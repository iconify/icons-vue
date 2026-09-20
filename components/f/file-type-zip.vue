<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGXr4mrHrF" x1="17.65" x2="21.099" y1="26.056" y2="26.056" gradientUnits="userSpaceOnUse"><stop offset="0" class="nbg31vb5l"/><stop offset=".5" class="vc--wpv5i"/><stop offset="1" class="nbg31vb5l"/></linearGradient><linearGradient id="SVG5oyStdai" x1="17.65" x2="21.099" y1="23.756" y2="23.756" href="#SVGXr4mrHrF"/><linearGradient id="SVG9QsNwcZU" x1="17.65" x2="21.099" y1="21.456" y2="21.456" href="#SVGXr4mrHrF"/><linearGradient id="SVG1kIgneZE" x1="17.65" x2="21.099" y1="19.156" y2="19.156" href="#SVGXr4mrHrF"/><linearGradient id="SVGp2oQjdFa" x1="17.65" x2="21.099" y1="16.857" y2="16.857" href="#SVGXr4mrHrF"/><linearGradient id="SVGAFV8AN5B" x1="17.65" x2="21.099" y1="14.557" y2="14.557" href="#SVGXr4mrHrF"/><linearGradient id="SVGRkU6lbfc" x1="17.65" x2="21.099" y1="12.257" y2="12.257" href="#SVGXr4mrHrF"/><linearGradient id="SVGWUBOGcFP" x1="17.65" x2="21.099" y1="9.957" y2="9.957" href="#SVGXr4mrHrF"/><linearGradient id="SVGFcdVfdXh" x1="17.65" x2="21.099" y1="7.657" y2="7.657" href="#SVGXr4mrHrF"/><linearGradient id="SVGLioYKc8j" x1="16.237" x2="19.686" y1="27.217" y2="27.217" href="#SVGXr4mrHrF"/><linearGradient id="SVGIx7REdei" x1="16.237" x2="19.686" y1="24.918" y2="24.918" href="#SVGXr4mrHrF"/><linearGradient id="SVGownHpeLf" x1="16.237" x2="19.686" y1="22.618" y2="22.618" href="#SVGXr4mrHrF"/><linearGradient id="SVGZ4gzmcVN" x1="16.237" x2="19.686" y1="20.318" y2="20.318" href="#SVGXr4mrHrF"/><linearGradient id="SVGhAblbd0u" x1="16.237" x2="19.686" y1="18.018" y2="18.018" href="#SVGXr4mrHrF"/><linearGradient id="SVGBzD5PbgA" x1="17.65" x2="21.099" y1="28.356" y2="28.356" href="#SVGXr4mrHrF"/><linearGradient id="SVGcXb6lbYS" x1="16.237" x2="19.686" y1="15.718" y2="15.718" href="#SVGXr4mrHrF"/><linearGradient id="SVGKF6nobvx" x1="16.237" x2="19.686" y1="13.419" y2="13.419" href="#SVGXr4mrHrF"/><linearGradient id="SVGrU8zSORM" x1="16.237" x2="19.686" y1="11.119" y2="11.119" href="#SVGXr4mrHrF"/><linearGradient id="SVGuFw9gbIu" x1="16.237" x2="19.686" y1="8.819" y2="8.819" href="#SVGXr4mrHrF"/><linearGradient id="SVGXh7zWblD" x1="16.237" x2="19.686" y1="29.514" y2="29.514" href="#SVGXr4mrHrF"/><linearGradient id="SVGmzaoUw6y" x1="16.985" x2="20.446" y1="11.196" y2="11.196" href="#SVGXr4mrHrF"/><linearGradient id="SVGkZYaOeHC" x1="18.096" x2="19.336" y1="5.329" y2="5.329" href="#SVGXr4mrHrF"/><linearGradient id="SVGVKO9QdOI" x1="16.029" x2="21.403" y1="5.591" y2="5.591" href="#SVGXr4mrHrF"/></defs><path class="ntfzo5t2w"/><path fill="url(#SVGXr4mrHrF)" class="y4xn9acaq"/><path fill="url(#SVG5oyStdai)" class="s3fhyyzft"/><path fill="url(#SVG9QsNwcZU)" class="z36hq9bxp"/><path fill="url(#SVG1kIgneZE)" class="x39a672ix"/><path fill="url(#SVGp2oQjdFa)" class="roye4-biy"/><path fill="url(#SVGAFV8AN5B)" class="h7v69tbqs"/><path fill="url(#SVGRkU6lbfc)" class="m41g82bos"/><path fill="url(#SVGWUBOGcFP)" class="q52aw3wzf"/><path fill="url(#SVGFcdVfdXh)" class="w2iembbfc"/><path fill="url(#SVGLioYKc8j)" class="uf-uus5gh"/><path fill="url(#SVGIx7REdei)" class="sybqi5bhl"/><path fill="url(#SVGownHpeLf)" class="r2gsdr79x"/><path fill="url(#SVGZ4gzmcVN)" class="pnbqd15el"/><path fill="url(#SVGhAblbd0u)" class="p_my1gk0y"/><path fill="url(#SVGBzD5PbgA)" class="pkpyb6b-k"/><path fill="url(#SVGcXb6lbYS)" class="lk6ttnbaf"/><path fill="url(#SVGKF6nobvx)" class="evnh8vnqy"/><path fill="url(#SVGrU8zSORM)" class="o7rtcdspm"/><path fill="url(#SVGuFw9gbIu)" class="ep-b7rk7x"/><path fill="url(#SVGXh7zWblD)" class="shs_r0bed"/><path fill="url(#SVGmzaoUw6y)" class="q6f88q_bz"/><path fill="url(#SVGkZYaOeHC)" class="ebf91593o"/><path fill="url(#SVGVKO9QdOI)" class="ap-takb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-zip" /></template>
<style>
.ap-takb1n {
  d: path("M21.4 4.56a2.55 2.55 0 0 0-2.549-2.549h-.276a2.55 2.55 0 0 0-2.436 3.3v.006a8 8 0 0 1 .261 2.561a1.8 1.8 0 0 0 .641 1.271l.109-3.441a.593.593 0 0 1 .6-.551h.135v-1.57h1.653v1.57h.1a.6.6 0 0 1 .605.551l.121 3.462a1.8 1.8 0 0 0 .666-1.292V7.72a7.7 7.7 0 0 1 .236-2.359a2.5 2.5 0 0 0 .134-.801");
}

.ebf91593o {
  d: path("M18.096 3.802h1.24v3.054h-1.24z");
}

.ep-b7rk7x {
  d: path("M16.237 8.322h3.45v.993h-3.45z");
}

.evnh8vnqy {
  d: path("M16.237 12.922h3.45v.993h-3.45z");
}

.h7v69tbqs {
  d: path("M17.65 14.06h3.45v.993h-3.45z");
}

.lk6ttnbaf {
  d: path("M16.237 15.222h3.45v.993h-3.45z");
}

.m41g82bos {
  d: path("M17.65 11.76h3.45v.993h-3.45z");
}

.nbg31vb5l {
  stop-color: var(--svg-color--4d4d4d, #4d4d4d);
}

.ntfzo5t2w {
  fill: var(--svg-color--c09553, #c09553);
  d: path("M27.667 27.667V17.333L23 15V2H4.333v28h23.334Zm-4.667 0v-9.111l2.333 1.222v7.889Z");
}

.o7rtcdspm {
  d: path("M16.237 10.622h3.45v.993h-3.45z");
}

.p_my1gk0y {
  d: path("M16.237 17.522h3.45v.993h-3.45z");
}

.pkpyb6b-k {
  d: path("M17.65 27.859h3.45v.993h-3.45z");
}

.pnbqd15el {
  d: path("M16.237 19.821h3.45v.993h-3.45z");
}

.q52aw3wzf {
  d: path("M17.65 9.461h3.45v.993h-3.45z");
}

.q6f88q_bz {
  d: path("M20.1 5.911a.554.554 0 0 0-.548-.53h-.009v.557h.092l.206 2.514h-2.252l.211-2.514h.094v-.557h-.044a.55.55 0 0 0-.547.53l-.314 10.569a.513.513 0 0 0 .515.531h2.432a.51.51 0 0 0 .513-.531Zm-1.384 10.5a1.171 1.171 0 1 1 1.171-1.171a1.17 1.17 0 0 1-1.171 1.168Z");
}

.r2gsdr79x {
  d: path("M16.237 22.121h3.45v.993h-3.45z");
}

.roye4-biy {
  d: path("M17.65 16.36h3.45v.993h-3.45z");
}

.s3fhyyzft {
  d: path("M17.65 23.26h3.45v.993h-3.45z");
}

.shs_r0bed {
  d: path("M16.237 29.018h3.45v.993h-3.45z");
}

.sybqi5bhl {
  d: path("M16.237 24.421h3.45v.993h-3.45z");
}

.uf-uus5gh {
  d: path("M16.237 26.721h3.45v.993h-3.45z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w2iembbfc {
  d: path("M17.65 7.161h3.45v.993h-3.45z");
}

.x39a672ix {
  d: path("M17.65 18.66h3.45v.993h-3.45z");
}

.y4xn9acaq {
  d: path("M17.65 25.559h3.45v.993h-3.45z");
}

.z36hq9bxp {
  d: path("M17.65 20.96h3.45v.993h-3.45z");
}

</style>
