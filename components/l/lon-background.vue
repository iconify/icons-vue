<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGgJDj2RwC)" class="r4i437pya"/><path clip-rule="evenodd" class="y-zgfkbmy"/><path clip-rule="evenodd" class="i3exb1bpu"/></g><defs><linearGradient id="SVGgJDj2RwC" x1="4.005" x2="20.004" y1="20.065" y2="20.065" gradientUnits="userSpaceOnUse"><stop class="m3j_j1b2v"/><stop offset="1" class="r4ff_7bxf"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lon-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i3exb1bpu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.935 9.505a4.76 4.76 0 0 1-3.138 4.486a4.73 4.73 0 0 1-5.721-2.117c-.2-.349-.357-.943-.464-1.448a.557.557 0 0 0-1.004-.2c-.417.603-.415 1.507-.343 2.2q0 .01.003.02q.038.378.135.745q.117.482.323.935c1 2.236 3.255 3.66 6.21 3.42c.291-.024.569-.113.855-.172c2.438-.512 4.194-2.713 4.209-5.305c0-2.08-.774-4.125-2.203-5.645a4.75 4.75 0 0 1 1.138 3.08");
}

.m3j_j1b2v {
  stop-color: var(--svg-color--2d2d4b, #2d2d4b);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4ff_7bxf {
  stop-color: var(--svg-color--1d1d3a, #1d1d3a);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.y-zgfkbmy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.048 4q-.43 0-.859.047C7.148 4.473 4 7.872 4 12.001c0 4.418 3.602 8 8.048 7.999h.018a8.04 8.04 0 0 0 3.68-.893c.325-.168.184-.657-.181-.646h-.015c-3.218.08-6.22-1.307-7.397-3.815c-.604-1.283-.826-2.326-.315-3.978c.169-.677.568-1.306 1.034-1.792q.053-.064.115-.121a1 1 0 0 1 .084-.076l.034-.034c.011-.008.018-.016.03-.024a.4.4 0 0 1 .067-.054c.794-.643 1.777-1.07 2.8-1.067c2.4 0 4.499 1.96 4.499 4.262c0 .791-.364 1.622-.804 2.282c1.92-.658 3.28-2.492 3.28-4.56a4.62 4.62 0 0 0-1.188-3.086a8 8 0 0 0-1.006-.867l-.003-.003A8.04 8.04 0 0 0 12.061 4z");
}

</style>
