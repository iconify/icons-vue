<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bob1habrm"/><path class="vfupgen9x"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kunci-background" /></template>
<style>
.bob1habrm {
  fill: var(--svg-color--703893, #703893);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vfupgen9x {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.139 8.21a3.89 3.89 0 0 0-3.747 2.947H4v1.685h8.387c.409 1.659 1.937 2.947 3.748 2.947A3.83 3.83 0 0 0 20 11.999c0-2.088-1.735-3.789-3.861-3.789m.072 5.895a2.106 2.106 0 1 1 0-4.212a2.106 2.106 0 0 1 0 4.212m-6.005-5.836c0 .623-.467 1.128-1.057 1.116c-.576 0-1.048-.506-1.035-1.137V8.21H7.107v.021c0 .623-.467 1.133-1.052 1.12c-.581 0-1.053-.505-1.04-1.141H4v2.526h7.145l.013-2.526h-.952zm6.847 3.73c0 .468-.56.843-1.264.843v-1.685c.691 0 1.264.375 1.264.842");
}

</style>
