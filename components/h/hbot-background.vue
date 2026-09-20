<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="xjtmxkbwc"/><path class="li828mb6z"/><path class="cbkspkbga"/><path class="hll7z9bxb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hbot-background" /></template>
<style>
.cbkspkbga {
  fill: var(--svg-color--a7a7a7, #a7a7a7);
  d: path("M14.068 15.733c-.71-1.2-.862-2.541-.488-3.537c1.035.134 2.132.898 2.843 2.102c.711 1.2.858 2.546.489 3.537q-.132-.017-.258-.045c-.955-.217-1.933-.95-2.586-2.052z");
}

.ft5dv1b6b {
  fill: none;
}

.hll7z9bxb {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.544 9.134a4.68 4.68 0 0 0-.311-3.576l-3.786 4.7c-.36-.217-.733-.404-1.12-.493a1.53 1.53 0 0 0-1.301.267c-.2.15-.311.342-.423.537c-.08.138-.16.28-.275.405c-.249.28-3.328 1.63-3.328 1.63l.044.103s2.875-1.289 3.457-1.182c.587.106 1.773.47 2.524 2.008c.8 1.622 2.328 2.622 3.181 2.497l-.826 2.404c4.265.209 2.746-3.421 1.43-5.243a9 9 0 0 0 1.68-.707c.32-.168.622-.386.898-.63a6.7 6.7 0 0 0 1.466-1.911a9.8 9.8 0 0 0 1.057-3.141L14.54 9.134z");
}

.li828mb6z {
  fill: var(--svg-color--676767, #676767);
  d: path("M15.49 15.199c-1.146-.791-1.834-1.942-1.91-3.004c.995-.324 2.302-.102 3.448.689c1.146.786 1.835 1.937 1.91 2.995c-.062.022-.124.044-.186.057c-.969.24-2.186 0-3.261-.742z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xjtmxkbwc {
  fill: var(--svg-color--2c2c2c, #2c2c2c);
  d: path("M16.623 13.963c-1.377-.169-2.506-.875-3.048-1.786c.742-.746 2.009-1.155 3.377-.986c1.377.168 2.506.875 3.048 1.786l-.129.12c-.755.67-1.955 1.026-3.248.866");
}

</style>
