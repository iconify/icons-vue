<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGMMTvQdSi" class="slfsbw7lf"/><path id="SVGFslDYdbM" class="z4ihlvt6x"/></defs><g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGVny1Bbjc)" clip-rule="evenodd" class="rm-fz8byy"/><use href="#SVGMMTvQdSi"/><path fill="url(#SVG7XEUYQFf)" class="kj0lcbbjm"/><use href="#SVGFslDYdbM"/><path fill="url(#SVGqQm8beva)" class="c5bt2pbpa"/><path fill="url(#SVGVny1Bbjc)" clip-rule="evenodd" class="rm-fz8byy"/><use href="#SVGMMTvQdSi"/><path fill="url(#SVG7XEUYQFf)" class="kj0lcbbjm"/><use href="#SVGFslDYdbM"/><path fill="url(#SVGqQm8beva)" class="c5bt2pbpa"/></g><defs><linearGradient id="SVGVny1Bbjc" x1="6.75" x2="17.25" y1="6" y2="18.25" gradientUnits="userSpaceOnUse"><stop class="os9aeqbuw"/><stop offset=".56" class="prdoc61dt"/><stop offset="1" class="cmavuzjzy"/></linearGradient><linearGradient id="SVG7XEUYQFf" x1="8" x2="20.746" y1="6.244" y2="13.371" gradientUnits="userSpaceOnUse"><stop class="cx_xa9jsx"/><stop offset="1" class="d6gvmca8f"/></linearGradient><linearGradient id="SVGqQm8beva" x1="6.25" x2="19.25" y1="6.75" y2="14" gradientUnits="userSpaceOnUse"><stop class="xg6kiebwj"/><stop offset="1" class="a9bph6ysg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ator-background" /></template>
<style>
.a9bph6ysg {
  stop-color: var(--svg-color--01678d, #01678d);
}

.c5bt2pbpa {
  d: path("M16.69 11.525c.36.185.8-.065.73-.46a5.5 5.5 0 0 0-10.85.08c-.065.38.35.625.69.45A10.2 10.2 0 0 1 12 10.5c1.74 0 3.34.34 4.69 1.025m3.235 1.585c-.245 1.745-2.45 1.8-3.985.925a7.96 7.96 0 0 0-7.88 0c-1.535.87-3.74.82-3.985-.925a8 8 0 1 1 15.85 0");
}

.cmavuzjzy {
  stop-color: var(--svg-color--065270, #065270);
}

.cx_xa9jsx {
  stop-color: var(--svg-color--025962, #025962);
}

.d6gvmca8f {
  stop-color: var(--svg-color--026d77, #026d77);
}

.ft5dv1b6b {
  fill: none;
}

.kj0lcbbjm {
  d: path("M15.94 14.035c1.535.87 3.74.82 3.985-.925a8 8 0 1 0-15.85 0c.245 1.745 2.45 1.8 3.985.925a7.96 7.96 0 0 1 7.88 0");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.os9aeqbuw {
  stop-color: var(--svg-color--025a63, #025a63);
}

.prdoc61dt {
  stop-color: var(--svg-color--026e7a, #026e7a);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rm-fz8byy {
  fill-rule: evenodd;
  d: path("M12 17.5a5.5 5.5 0 1 0 0-11a5.5 5.5 0 0 0 0 11m0 2.5a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.slfsbw7lf {
  fill: var(--svg-color--005257, #005257);
  d: path("M16.66 14.925A.8.8 0 0 0 17 15l.34.01c.975.05 2.415.115 2.635-2.345q.024-.329.025-.665h-2.5c0 1.075-.31 2.08-.84 2.925M4.4 14.5c.335.3.845.5 1.6.5c.5 0 .93-.05 1.305-.135A5.5 5.5 0 0 1 6.5 12H4c0 .875.14 1.715.4 2.5");
}

.xg6kiebwj {
  stop-color: var(--svg-color--02bfc5, #02bfc5);
}

.z4ihlvt6x {
  fill: var(--svg-color--005560, #005560);
  d: path("M8.5 12c-1.6-.4-3-2.5-3.5-3.5v2.25l2 2.75z");
}

</style>
