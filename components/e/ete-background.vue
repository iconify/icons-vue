<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t9xvd5bjm"/><path class="vbqr-xxhj"/><path class="f71fpd-gp"/><path class="yn5_v9wmk"/><path class="oiuj92bbc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ete-background" /></template>
<style>
.f71fpd-gp {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.79 10.154L7.974 11.88l3.814 2.29v-.336l-3.242-1.911l3.242-1.449zm0 .556l-2.763 1.242l2.762 1.625v-.35l-2.037-1.22l2.037-.918zm0 .627l-1.525.674l1.524.926zm-4.842.981l4.841 2.91v-.842l-4.05-2.442zm9.027-.58c.345.152 1.044.463 1.077.472L12.211 4v.85l4.092 6.93l-.42-.168L12.21 5.06v6.475l1.377.518l2.425-.168z");
}

.ft5dv1b6b {
  fill: none;
}

.oiuj92bbc {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.97 16.127c-.059 0-3.372-1.908-5.022-2.863L11.97 20l5.082-6.736a260 260 0 0 1-5.082 2.863");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t9xvd5bjm {
  fill: var(--svg-color--10acf9, #10acf9);
  d: path("M24 0H0v24h24z");
}

.vbqr-xxhj {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.025 11.73c-.345.156-1.044.467-1.077.476L11.789 4v.85l-4.092 6.926l.421-.168l3.671-6.547v6.475l-1.376.514l-2.426-.169l.038-.147z");
}

.yn5_v9wmk {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.21 10.154l3.815 1.718l-3.814 2.282v-.337l3.242-1.903l-3.242-1.44zm0 .552l2.763 1.238l-2.762 1.616v-.345l2.037-1.217l-2.037-.917v-.38zm0 2.219v-1.592l1.525.674zm4.842-.62l-4.841 2.906v-.842l4.05-2.43z");
}

</style>
