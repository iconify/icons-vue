<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGnYzo0doU)" class="r4i437pya"/><path class="sgi8i7bln"/></g><defs><linearGradient id="SVGnYzo0doU" x1="4" x2="20" y1="11.999" y2="11.999" gradientUnits="userSpaceOnUse"><stop class="y1nt4abzr"/><stop offset=".23" class="czr822ilr"/><stop offset=".52" class="q104xjbgq"/><stop offset=".74" class="imuiplmqx"/><stop offset=".9" class="ses-2u7_r"/><stop offset="1" class="e5gwm5bdm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:krom-background" /></template>
<style>
.czr822ilr {
  stop-color: var(--svg-color--aac5f9, #aac5f9);
}

.e5gwm5bdm {
  stop-color: var(--svg-color--aea0f4, #aea0f4);
}

.ft5dv1b6b {
  fill: none;
}

.imuiplmqx {
  stop-color: var(--svg-color--b6b5f7, #b6b5f7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q104xjbgq {
  stop-color: var(--svg-color--a5bcf8, #a5bcf8);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ses-2u7_r {
  stop-color: var(--svg-color--ebb0f2, #ebb0f2);
}

.sgi8i7bln {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.555 18.629l-6.523-5.553l-6.699 5.665c-.517.437-1.333.085-1.333-.582V5.84c0-.667.816-1.014 1.333-.582l6.7 5.691l6.58-5.616a.853.853 0 0 1 1.174.064a.78.78 0 0 1-.07 1.136l-6.42 5.451l6.373 5.44a.783.783 0 0 1 .08 1.13a.865.865 0 0 1-1.195.075M5.6 7.54v8.87l5.168-4.406z");
}

.y1nt4abzr {
  stop-color: var(--svg-color--9eebfd, #9eebfd);
}

</style>
