<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGXwBZNc0L)" class="qe49nw99x"/><path fill="url(#SVGaxgDpTIp)" class="m4d9sabvo"/><path class="djy7fibil"/><defs><linearGradient id="SVGXwBZNc0L" x1="12" x2="12" y1="3.241" y2="20.713" gradientUnits="userSpaceOnUse"><stop class="adpycpbam"/><stop offset="1" class="gci8bebnw"/></linearGradient><linearGradient id="SVGaxgDpTIp" x1="-1.288" x2="16.084" y1="7.865" y2="25.881" gradientUnits="userSpaceOnUse"><stop class="adpycpbam"/><stop offset=".739" class="gci8bebnw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:klv" /></template>
<style>
.adpycpbam {
  stop-color: var(--svg-color--ff4681, #ff4681);
}

.djy7fibil {
  fill: var(--svg-color--000, #000);
  d: path("M21 20.678L16.665 16.5l1-.964z");
  opacity: var(--svg-opacity--0-14, 0.14);
}

.ft5dv1b6b {
  fill: none;
}

.gci8bebnw {
  stop-color: var(--svg-color--9b44f6, #9b44f6);
}

.m4d9sabvo {
  d: path("M21 20.678H3V3.321z");
}

.qe49nw99x {
  d: path("M21 20.678h-8.666L21 12.321z");
}

</style>
