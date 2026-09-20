<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG7ZXzIjRM)" class="jkyeqkg5k"/><path fill="url(#SVGfQGvDegm)" class="d6gt3cb_g"/><path fill="url(#SVGGprAGi3h)" class="e2n6fh-fj"/><defs><linearGradient id="SVG7ZXzIjRM" x1="18.019" x2="15.702" y1="8.28" y2="17.43" gradientUnits="userSpaceOnUse"><stop class="ge0suc4ov"/><stop offset=".8" class="rrlothbbr"/></linearGradient><linearGradient id="SVGfQGvDegm" x1="11.999" x2="16.093" y1="16.5" y2="7.344" gradientUnits="userSpaceOnUse"><stop class="l2bw37dxp"/><stop offset=".39" class="izod3cbgs"/><stop offset="1" class="l2bw37dxp"/></linearGradient><linearGradient id="SVGGprAGi3h" x1="3.162" x2="18.84" y1="16.499" y2="2.716" gradientUnits="userSpaceOnUse"><stop class="dewvcbcde"/><stop offset=".65" class="hlfk8gr7p"/><stop offset=".92" class="ohk1iabge"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hook" /></template>
<style>
.d6gt3cb_g {
  d: path("M16.517 16.5c-2.155 0-3.51-1.395-3.915-2.088l3.213-.693l-.89.693c2.038 1.454 4.724-.383 4.724-2.295c0-1.534-1.278-2.529-1.854-2.835c1.737.243 2.89 1.422 3.006 1.8c.095.306.198.68.198 1.035c0 2.156-1.786 4.383-4.482 4.383");
}

.dewvcbcde {
  stop-color: var(--svg-color--adf160, #adf160);
}

.e2n6fh-fj {
  d: path("M6.407 14.893a3.92 3.92 0 0 1-3.24-1.62c.247 1.53 2.025 3.227 4.37 3.227c1.88 0 3.518-1.643 4.103-2.466l2.313-3.416c.432-.526 1.67-1.58 3.132-1.58s3.217 1.054 3.915 1.58c-.297-1.03-1.498-3.087-3.915-3.087s-4.063 1.71-4.59 2.565c-.877 1.188-2.713 3.65-3.046 3.938c-.414.36-.81.859-3.042.859");
}

.ft5dv1b6b {
  fill: none;
}

.ge0suc4ov {
  stop-color: var(--svg-color--68d869, #68d869);
}

.hlfk8gr7p {
  stop-color: var(--svg-color--17b6d7, #17b6d7);
}

.izod3cbgs {
  stop-color: var(--svg-color--1bb8ca, #1bb8ca);
}

.jkyeqkg5k {
  d: path("M7.482 7.5c2.155 0 3.51 1.395 3.915 2.088l-3.213.693l.89-.693C7.037 8.134 4.35 9.97 4.35 11.883c0 1.534 1.278 2.529 1.854 2.835c-1.737-.243-2.889-1.422-3.006-1.8A3.6 3.6 0 0 1 3 11.883C3 9.732 4.786 7.5 7.482 7.5");
}

.l2bw37dxp {
  stop-color: var(--svg-color--1cd7ca, #1cd7ca);
}

.ohk1iabge {
  stop-color: var(--svg-color--0061a0, #0061a0);
}

.rrlothbbr {
  stop-color: var(--svg-color--c6f88a, #c6f88a);
}

</style>
