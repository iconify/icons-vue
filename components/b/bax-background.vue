<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f6cqdlbay"/><path clip-rule="evenodd" class="vyxxye-4c"/><path clip-rule="evenodd" class="sexc63byl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bax-background" /></template>
<style>
.f6cqdlbay {
  fill: var(--svg-color--70b1c7, #70b1c7);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sexc63byl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.035 13.381A5.54 5.54 0 1 0 7.05 5.7c-2.41 2.505-2.565 6.661-2.46 9.995a.523.523 0 0 0 .527.507c3.313-.024 7.523-.329 9.92-2.821m-.89-.658A4.445 4.445 0 0 0 7.74 6.561c-1.908 1.984-2.054 5.26-1.976 7.917a.52.52 0 0 0 .527.507c2.643-.025 5.958-.288 7.857-2.262");
}

.vyxxye-4c {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.26 18.355a5.541 5.541 0 0 0-6.733-8.802c-2.76 2.112-3.543 6.198-3.943 9.509a.52.52 0 0 0 .444.58c3.28.478 7.486.813 10.232-1.287m-.78-.785a4.444 4.444 0 1 0-5.402-7.06c-2.186 1.672-2.826 4.888-3.151 7.526a.52.52 0 0 0 .445.58c2.615.377 5.933.617 8.108-1.046");
}

</style>
