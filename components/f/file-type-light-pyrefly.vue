<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGbbFy6ccS" x1="244.69" x2="244.69" y1="178.14" y2="77.23" gradientUnits="userSpaceOnUse"><stop offset="0" class="xv2xe3f4o"/><stop offset="1" class="nl3nmg5at"/></linearGradient><linearGradient id="SVG6FR4Vdvy" x1="243.99" x2="243.99" y1="356.44" y2="129.44" gradientUnits="userSpaceOnUse"><stop offset=".15" class="d6sp1rbwk"/><stop offset=".85" class="v9yih4bbe"/></linearGradient><path id="SVGtinHydUm" fill="url(#SVG6FR4Vdvy)" class="o2sbcacyk"/></defs><path fill="url(#SVGbbFy6ccS)" transform="translate(-.03 3.34)scale(.06551)" class="n2kabpbau"/><path class="l793z-bpu"/><use href="#SVGtinHydUm" transform="translate(-.03 3.34)scale(.06551)"/><use href="#SVGtinHydUm" transform="translate(-.03 3.34)scale(.06551)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-pyrefly" /></template>
<style>
.d6sp1rbwk {
  stop-color: var(--svg-color--ff4602, #ff4602);
}

.l793z-bpu {
  fill: var(--svg-color--394048, #394048);
  d: path("M18.4 8.16v-.39a2.46 2.46 0 1 0-4.92 0v.36L2 5.56a8.3 8.3 0 0 0 6.11 5.68a8.2 8.2 0 0 0 5.67-.75q.43-.23.83-.5L16 9.04l1.38.93l.08.05l.39.25l.34.19l.03.02a8.3 8.3 0 0 0 5.66.75A8.3 8.3 0 0 0 30 5.56z");
}

.n2kabpbau {
  d: path("M244.69 77.23L75.41 159.31c62.43 38.76 112.53 9.97 141.57-17.49q.03-.06.06-.06c17.19-16.29 27-32.09 27.61-33.08l.04-.06l.04.06c.61.99 10.42 16.79 27.61 33.08q.03 0 .06.06c29.04 27.46 79.14 56.25 141.57 17.49z");
}

.nl3nmg5at {
  stop-color: var(--svg-color--6d737a, #6d737a);
}

.o2sbcacyk {
  d: path("M268.84 311.09a136 136 0 0 1-8.14 9.81c.29-25.86-3.51-34.7-16.86-50.02l-.11-.04c-24.56 42.71-16.79 82.38-16.14 85.41l.04.1l.02.1c-32.32-50.92-42.72-90.71-41.77-121.35c.21-7.15 1.31-13.78 2.36-20.01c2.73-16.39 10.12-29.8 18.69-40.38l1.39-1.68l36.36-43.58l37.66 45.13l1.62 1.94c11 13.63 16.27 27.96 17.76 42.11c4.04 38.38-19.8 75.37-32.87 92.46z");
}

.v9yih4bbe {
  stop-color: var(--svg-color--ff9a00, #ff9a00);
}

.xv2xe3f4o {
  stop-color: var(--svg-color--bdc5cf, #bdc5cf);
}

</style>
