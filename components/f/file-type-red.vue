<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGGkOCIeZk" x1="-547.975" x2="-547" y1="-244.974" y2="-244.974" gradientTransform="matrix(4 0 0 -4 2204 -974)" gradientUnits="userSpaceOnUse"><stop offset="0" class="oyey6ql1o"/><stop offset="1" class="smzaobguw"/></linearGradient><linearGradient id="SVGJknVZd9g" x1="-547" x2="-544.762" y1="-247.171" y2="-247.171" gradientTransform="matrix(4 0 0 -4 2204 -974)" gradientUnits="userSpaceOnUse"><stop offset="0" class="pkl08ubxc"/><stop offset=".583" class="y_6-cwvsq"/><stop offset="1" class="q8q3clbbp"/></linearGradient><linearGradient id="SVGFJHXfduf" x1="-547" x2="-546.025" y1="-244.974" y2="-244.974" gradientTransform="matrix(4 0 0 -4 2204 -974)" gradientUnits="userSpaceOnUse"><stop offset="0" class="c7l6a6bqu"/><stop offset=".612" class="v3dhx9bkq"/><stop offset="1" class="gfif-jskx"/></linearGradient><linearGradient id="SVG6PN03b4W" x2="-543.5" y1="-249.368" y2="-249.368" href="#SVGJknVZd9g"/><linearGradient id="SVGpajdab2d" x1="-550.5" x2="-547" y1="-249.368" y2="-249.368" gradientTransform="matrix(4 0 0 -4 2204 -974)" gradientUnits="userSpaceOnUse"><stop offset="0" class="p_vy-d1vm"/><stop offset=".563" class="enanyz0nq"/><stop offset="1" class="rjkjfacro"/></linearGradient><linearGradient id="SVGEmUtNbNW" x1="-549.238" y1="-247.171" y2="-247.171" href="#SVGpajdab2d"/></defs><path fill="url(#SVGGkOCIeZk)" class="yicm5xbec"/><path fill="url(#SVGJknVZd9g)" class="yhmirc9ct"/><path fill="url(#SVGFJHXfduf)" class="yzv6u2b8o"/><path fill="url(#SVG6PN03b4W)" class="jr6a9mbmr"/><path fill="url(#SVGpajdab2d)" class="zztrlibvx"/><path fill="url(#SVGEmUtNbNW)" class="a7dl3pvzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-red" /></template>
<style>
.a7dl3pvzq {
  d: path("m10.952 9.467l-3.904 5.769L16 19.903v-7.806z");
}

.c7l6a6bqu {
  stop-color: var(--svg-color--e8a333, #e8a333);
}

.enanyz0nq {
  stop-color: var(--svg-color--d01d19, #d01d19);
}

.gfif-jskx {
  stop-color: var(--svg-color--ab762f, #ab762f);
}

.jr6a9mbmr {
  d: path("M26.097 16.947L16 22.208V30l14-7.283z");
}

.oyey6ql1o {
  stop-color: var(--svg-color--eea831, #eea831);
}

.p_vy-d1vm {
  stop-color: var(--svg-color--ae2524, #ae2524);
}

.pkl08ubxc {
  stop-color: var(--svg-color--b32629, #b32629);
}

.q8q3clbbp {
  stop-color: var(--svg-color--7a1a1d, #7a1a1d);
}

.rjkjfacro {
  stop-color: var(--svg-color--ed1913, #ed1913);
}

.smzaobguw {
  stop-color: var(--svg-color--ffc929, #ffc929);
}

.v3dhx9bkq {
  stop-color: var(--svg-color--c68931, #c68931);
}

.y_6-cwvsq {
  stop-color: var(--svg-color--8c1e21, #8c1e21);
}

.yhmirc9ct {
  d: path("M16 12.097v7.806l8.952-4.667l-3.904-5.769z");
}

.yicm5xbec {
  d: path("M16 9.792V2l-3.903 5.77z");
}

.yzv6u2b8o {
  d: path("m16 9.792l3.903-2.022L16 2z");
}

.zztrlibvx {
  d: path("M2 22.717L16 30v-7.792L5.903 16.947z");
}

</style>
