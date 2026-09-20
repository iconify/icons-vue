<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="kqfoc3agu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lens-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kqfoc3agu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.032 9.74a2.85 2.85 0 0 1 1.942-.772A3.03 3.03 0 0 1 20 11.997c0 1.447-1.432 2.685-1.79 2.97c-1.675 1.334-3.856 2.113-6.21 2.113s-4.535-.78-6.21-2.113C5.434 14.682 4 13.442 4 11.997a3.027 3.027 0 0 1 3.025-3.03c.753 0 1.429.296 1.943.772l.053-.026C9.14 8.15 10.41 6.92 12 6.92s2.86 1.231 2.979 2.793zm.604 3.01c.23.23.395.508.486.811h.002a.244.244 0 0 1-.195.307a.245.245 0 0 1-.273-.173a1.46 1.46 0 0 0-1.445-1.028l-.044.002a.643.643 0 1 1-.867.35q-.043.037-.083.076c-.171.17-.293.377-.363.6a.243.243 0 0 1-.272.173a.244.244 0 0 1-.195-.307a1.94 1.94 0 0 1 1.868-1.382c.52 0 1.013.203 1.38.572m-5.933-.083l.045-.002a1.46 1.46 0 0 1 1.4 1.03a.245.245 0 0 0 .272.173a.244.244 0 0 0 .196-.307a1.9 1.9 0 0 0-.487-.81a1.94 1.94 0 0 0-1.381-.572a1.94 1.94 0 0 0-1.868 1.382a.244.244 0 0 0 .195.307a.243.243 0 0 0 .273-.173a1.45 1.45 0 0 1 .446-.675a.643.643 0 1 0 .867-.35h-.003q.023 0 .045-.003m2.3 2.352c.374 0 .715-.143.976-.375a.25.25 0 0 1 .33-.004a.24.24 0 0 1 .006.358a1.944 1.944 0 0 1-2.625 0a.24.24 0 0 1 .006-.358a.246.246 0 0 1 .33.004c.258.232.602.375.976.375");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
