<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGcCPZacbV)" class="r4i437pya"/><path clip-rule="evenodd" class="ln7axvh5r"/></g><defs><linearGradient id="SVGcCPZacbV" x1="19.461" x2="4.24" y1="10.269" y2="10.269" gradientUnits="userSpaceOnUse"><stop offset=".12" class="f-mh4mr2d"/><stop offset="1" class="c8q_4prir"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:klt-background" /></template>
<style>
.c8q_4prir {
  stop-color: var(--svg-color--0aaef3, #0aaef3);
}

.f-mh4mr2d {
  stop-color: var(--svg-color--a157fd, #a157fd);
}

.ft5dv1b6b {
  fill: none;
}

.ln7axvh5r {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M14.876 6.316h-.77v1.6c-.674-.556-1.836-1.179-3.411-1.179h-.072a5.35 5.35 0 0 0-4.766 2.947H4v1.264h1.402a5.4 5.4 0 0 0-.139 1.233c0 3.04 2.425 5.504 5.423 5.504h.22c1.233 0 2.23-1.015 2.23-2.266v-.135a2.19 2.19 0 0 0-2.172-2.206h-.202a1.85 1.85 0 0 0-1.667 1.074c-.194.412.193.8.648.8c.202 0 .362-.177.455-.358a.76.76 0 0 1 .678-.421h.097a.986.986 0 0 1 .985 1.002v.257c0 .59-.472 1.074-1.053 1.074h-.307a4.21 4.21 0 0 1-4.156-4.253c0-.45.067-.893.194-1.306H20V9.685h-1.688c-.11-1.878-1.605-3.368-3.436-3.368m-.632 3.368c-1.094-1.52-2.665-1.886-3.38-1.87h-.08c-1.458 0-2.746.742-3.538 1.87zm2.994 0h-1.87V7.588l.144.029c1.01.194 1.633 1.048 1.726 2.067");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
