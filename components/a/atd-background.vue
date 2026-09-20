<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGbkFYbnml)" class="bzilf3uew"/><path class="acw04y32r"/><path class="cp23zrpiy"/><path fill="url(#SVGOv63ZcCu)" class="npc05zg1k"/></g><defs><linearGradient id="SVGbkFYbnml" x1="12.264" x2="12.264" y1="4" y2="6.666" gradientUnits="userSpaceOnUse"><stop class="dm0z560dg"/><stop offset="1" class="ugj5r2bgd"/></linearGradient><linearGradient id="SVGOv63ZcCu" x1="14.398" x2="13.331" y1="13.332" y2="14.132" gradientUnits="userSpaceOnUse"><stop class="ev-2s7erj"/><stop offset="1" class="zjsj_eomt"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atd-background" /></template>
<style>
.acw04y32r {
  fill: var(--svg-color--610467, #610467);
  d: path("M6.751 17.864c-.629 0-1.14.415-1.14 1.023a1.12 1.12 0 0 0 1.14 1.11h10.505a1.12 1.12 0 0 0 1.14-1.11c0-.608-.51-1.024-1.14-1.024z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bzilf3uew {
  d: path("M12.264 6.666a1.333 1.333 0 1 0 0-2.665a1.333 1.333 0 0 0 0 2.665");
}

.cp23zrpiy {
  fill: var(--svg-color--610467, #610467);
  d: path("M6.107 19.822a1.12 1.12 0 0 0 1.54-.326l3.104-4.73a1.093 1.093 0 0 0-.325-1.524a1.12 1.12 0 0 0-1.541.325l-3.103 4.73a1.093 1.093 0 0 0 .325 1.525");
}

.dm0z560dg {
  stop-color: var(--svg-color--e4396a, #e4396a);
}

.ev-2s7erj {
  stop-color: var(--svg-color--d12d6d, #d12d6d);
}

.ft5dv1b6b {
  fill: none;
}

.npc05zg1k {
  d: path("M9.273 7.936a1.083 1.083 0 0 0-.266 1.535l7.348 10.068a1.15 1.15 0 0 0 1.572.256a1.085 1.085 0 0 0 .262-1.536L10.84 8.192a1.145 1.145 0 0 0-1.568-.256");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ugj5r2bgd {
  stop-color: var(--svg-color--300f39, #300f39);
}

.zjsj_eomt {
  stop-color: var(--svg-color--610467, #610467);
}

</style>
