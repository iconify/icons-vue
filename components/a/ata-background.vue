<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGqG2sqepB)" class="jrm-t_hzk"/><path fill="url(#SVGS4gz9bwW)" class="evq5rou-s"/><path fill="url(#SVGNche5d4O)" class="vb2jey48x"/></g><defs><linearGradient id="SVGqG2sqepB" x1="14.111" x2="5.169" y1="4.844" y2="17.833" gradientUnits="userSpaceOnUse"><stop class="qj2numbbd"/><stop offset="1" class="fiy11wxak"/></linearGradient><linearGradient id="SVGS4gz9bwW" x1="7.665" x2="13.476" y1="4.257" y2="20.52" gradientUnits="userSpaceOnUse"><stop offset=".05" class="skzipr1zn"/><stop offset=".93" class="te1o4ry8t"/></linearGradient><linearGradient id="SVGNche5d4O" x1="3.998" x2="17.078" y1="16.938" y2="16.938" gradientUnits="userSpaceOnUse"><stop offset=".16" class="qj2numbbd"/><stop offset="1" class="fiy11wxak"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ata-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.evq5rou-s {
  d: path("M16.008 5.982c.305.32.605.685.84 1.1l2.449 4.338c1.694 3.009.15 6.708-2.749 7.932l-.695.195c2.074-2.214 1.59-4.628 1.01-5.638a2 2 0 0 0-.08-.165L13.42 7.952a1.395 1.395 0 0 0-1.884-.51a4.45 4.45 0 0 1 4.473-1.46");
}

.fiy11wxak {
  stop-color: var(--svg-color--ab1414, #ab1414);
}

.ft5dv1b6b {
  fill: none;
}

.jrm-t_hzk {
  d: path("M16.009 5.983a5.535 5.535 0 0 0-8.847 1.1L4.718 11.42c-.125.215-.23.44-.32.66l.01.02c.245 1.034.95 3.448 3.964 3.813c.165.02.315.03.46.03a1.385 1.385 0 0 1-1.195-2.07l3.379-5.887c.115-.2.37-.45.54-.565c.834-.9 2.269-1.794 4.453-1.439");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qj2numbbd {
  stop-color: var(--svg-color--fcca02, #fcca02);
}

.skzipr1zn {
  stop-color: var(--svg-color--aa1215, #aa1215);
}

.te1o4ry8t {
  stop-color: var(--svg-color--fdcb02, #fdcb02);
}

.vb2jey48x {
  d: path("M15.879 19.532c2.074-2.214 1.619-4.508 1.044-5.523c.375.89-.335 1.74-1.34 1.74H8.498c-3.014-.37-3.819-2.53-4.069-3.564l-.02-.11c-1.454 3.549 1.145 7.672 5.143 7.672h4.738c.635 0 1.125-.115 1.585-.215z");
}

</style>
