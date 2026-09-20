<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="k10uy9baf"/><path class="nrzwpbbph"/><path class="njc58b39z"/><path class="d7wn1bctj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:grg-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.d7wn1bctj {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.333 4l-.889 6.222l5.334 5.334z");
}

.ft5dv1b6b {
  fill: none;
}

.k10uy9baf {
  fill: var(--svg-color--054186, #054186);
  d: path("M12.667 20a7.111 7.111 0 1 0 0-14.223a7.111 7.111 0 0 0 0 14.223");
}

.njc58b39z {
  fill: var(--svg-color--ffca57, #ffca57);
  d: path("m10.444 10.223l-6.222.889l11.556 4.444z");
}

.nrzwpbbph {
  fill: var(--svg-color--ffae00, #ffae00);
  d: path("M10.444 10.222L11.334 4l-7.112 7.111z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
