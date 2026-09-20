<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGgoDI2cJh)" clip-rule="evenodd" class="d1cmnmyij"/><path fill="url(#SVG4iGQabml)" clip-rule="evenodd" class="ub74spbmv"/><path fill="url(#SVGWYLlFcEX)" clip-rule="evenodd" class="pgbu0jb7m"/></g><defs><linearGradient id="SVGgoDI2cJh" x1="804" x2="804" y1="48.83" y2="1583.48" gradientUnits="userSpaceOnUse"><stop class="he9fa_pkm"/><stop offset="1" class="f-kr6z77o"/></linearGradient><linearGradient id="SVG4iGQabml" x1="804" x2="804" y1="7.692" y2="1172.26" gradientUnits="userSpaceOnUse"><stop class="m8llqqb3s"/><stop offset="1" class="xxmqfqauw"/></linearGradient><linearGradient id="SVGWYLlFcEX" x1="804" x2="804" y1="34.511" y2="852.613" gradientUnits="userSpaceOnUse"><stop class="aphfj3b8a"/><stop offset="1" class="t9y8jcbfy"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blue-background" /></template>
<style>
.aphfj3b8a {
  stop-color: var(--svg-color--8bd7f9, #8bd7f9);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.d1cmnmyij {
  fill-rule: evenodd;
  d: path("M8.71 4h6.58c1.638 0 2.232.168 2.83.484c.6.316 1.07.78 1.39 1.371S20 7.033 20 8.65v6.497c0 1.616-.17 2.203-.49 2.793a3.3 3.3 0 0 1-1.39 1.371c-.598.317-1.192.485-2.83.485H8.71c-1.638 0-2.232-.169-2.83-.485a3.3 3.3 0 0 1-1.39-1.37C4.17 17.35 4 16.763 4 15.147V8.649c0-1.616.17-2.203.49-2.794a3.3 3.3 0 0 1 1.39-1.37C6.477 4.167 7.071 4 8.71 4");
}

.f-kr6z77o {
  stop-color: var(--svg-color--0c2550, #0c2550);
}

.ft5dv1b6b {
  fill: none;
}

.he9fa_pkm {
  stop-color: var(--svg-color--174697, #174697);
}

.m8llqqb3s {
  stop-color: var(--svg-color--3f78dc, #3f78dc);
}

.pgbu0jb7m {
  fill-rule: evenodd;
  d: path("M7.744 11.59h8.512c1.096 0 1.647.142 2.154.41c.506.267.904.66 1.175 1.16c.27.5.415 1.043.415 2.126v1.018c0 1.083-.144 1.626-.415 2.126s-.669.893-1.175 1.16c-.507.268-1.058.41-2.154.41H7.744c-1.096 0-1.647-.142-2.154-.41a2.8 2.8 0 0 1-1.175-1.16c-.27-.5-.415-1.043-.415-2.126v-1.018c0-1.083.144-1.626.415-2.126s.669-.893 1.175-1.16c.507-.268 1.058-.41 2.154-.41");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t9y8jcbfy {
  stop-color: var(--svg-color--68bbe1, #68bbe1);
}

.ub74spbmv {
  fill-rule: evenodd;
  d: path("M8.71 7.692h6.58c1.638 0 2.232.169 2.83.485c.6.316 1.07.78 1.39 1.37c.32.592.49 1.178.49 2.794v2.6c0 1.616-.17 2.202-.49 2.794a3.3 3.3 0 0 1-1.39 1.37c-.598.317-1.192.485-2.83.485H8.71c-1.638 0-2.232-.168-2.83-.485a3.3 3.3 0 0 1-1.39-1.37C4.17 17.144 4 16.557 4 14.94v-2.6c0-1.616.17-2.202.49-2.793s.79-1.055 1.39-1.371c.598-.316 1.192-.485 2.83-.485");
}

.xxmqfqauw {
  stop-color: var(--svg-color--2f5fb3, #2f5fb3);
}

</style>
