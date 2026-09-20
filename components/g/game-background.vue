<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGL0LLTdHP)" class="r4i437pya"/><path clip-rule="evenodd" class="rk44dkv6f"/></g><defs><linearGradient id="SVGL0LLTdHP" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="zkdjv7bkb"/><stop offset="1" class="jlm57rbiy"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:game-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jlm57rbiy {
  stop-color: var(--svg-color--82c742, #82c742);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rk44dkv6f {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.012 19.413a8 8 0 0 1-10.401-4.34c.046-1.912 1.71-4.933 5.155-5.933a4 4 0 0 0-1.426 3.906c.098 1.147.528 2.61 1.549 3.851c1.036 1.262 2.666 2.276 5.123 2.516m.982-.48c-2.867-.037-4.634-1.085-5.693-2.375a6.3 6.3 0 0 1-.915-1.514a4 4 0 0 0 6.65-1.441c.572.005 1.363.095 2.001.402c.326.158.6.367.79.64c.179.259.291.59.285 1.021a8.04 8.04 0 0 1-3.118 3.267M19.5 14.79A8 8 0 0 0 20 12c0-.96-.953-1.601-1.912-1.601h-2.624v.001H12.67c-.663 0-1.101.299-1.101.962c0 1.104.796 1.705 1.9 1.705h2.716l-.001.005c.598.019 1.402.123 2.085.453c.385.185.741.448.997.816q.142.205.235.449M11.93 8.277l.175-.01h3.63A4.267 4.267 0 0 0 20 4h-8a8 8 0 0 0-7.76 9.956c.642-2.478 3.172-5.558 7.689-5.679m1.669 2.923a.267.267 0 0 1 .533 0v.267h.267a.267.267 0 0 1 0 .533h-.267v.267a.267.267 0 0 1-.533 0V12h-.267a.267.267 0 0 1 0-.533h.267zm4.267 0a.267.267 0 1 1-.534 0a.267.267 0 0 1 .534 0m-.534.534a.267.267 0 1 1-.534-.001a.267.267 0 0 1 .534 0m.8.266a.267.267 0 1 0 0-.534a.267.267 0 0 0 0 .534m-.266.267a.267.267 0 1 1-.534 0a.267.267 0 0 1 .534 0");
}

.zkdjv7bkb {
  stop-color: var(--svg-color--0b9946, #0b9946);
}

</style>
