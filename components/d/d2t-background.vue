<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="wz2_n6b-h"/><path class="d_qkl-_ew"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:d2t-background" /></template>
<style>
.d_qkl-_ew {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.986 17.89A9.6 9.6 0 0 1 4 12.033c0-2.167.716-4.165 1.926-5.779H8.54c.626.042 2.07.193 2.841.506c.03-.301.24-.975.855-1.216c.77-.3 1.035-.3 2.516-.3c.813 0 1.48.041 2.083.077c.5.03.963.06 1.42.06c.813 0 1.505-.27 1.746-.409a2.48 2.48 0 0 1-1.926 1.445c-.301.048-.632.084-.963.12c-1.222.139-2.444.271-2.57.867c-.127.602.252 1.385.463 1.71c.24.421.686 1.432.572 2.143a7 7 0 0 1-.157.782a.7.7 0 0 0-.03.283c.018.18.512 1.842.758 2.649c.12.138.392.47.518.698c.163.283.313.752-.102 1.685c-.421.94-1.415 1.674-2.306 1.674c-.547 0-.818-.337-1.047-.632c-.145-.18-.277-.343-.452-.404c-.096-.036-.27-.066-.505-.108c-.897-.168-2.6-.482-3.473-1.535c-.596.24-1.915.873-2.794 1.541");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.wz2_n6b-h {
  fill: var(--svg-color--37c0d2, #37c0d2);
  d: path("M24 0H0v24h24z");
}

</style>
