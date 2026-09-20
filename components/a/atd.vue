<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG4ilf7bWa)" class="vu42odb2b"/><path class="p6y3rlbod"/><path class="wgrsohb1d"/><path fill="url(#SVGCSO5RQzw)" class="cjr9z7bwu"/><defs><linearGradient id="SVG4ilf7bWa" x1="12.297" x2="12.297" y1="3" y2="5.999" gradientUnits="userSpaceOnUse"><stop class="dm0z560dg"/><stop offset="1" class="ugj5r2bgd"/></linearGradient><linearGradient id="SVGCSO5RQzw" x1="14.697" x2="13.498" y1="13.498" y2="14.398" gradientUnits="userSpaceOnUse"><stop class="ev-2s7erj"/><stop offset="1" class="zjsj_eomt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:atd" /></template>
<style>
.cjr9z7bwu {
  d: path("M8.932 7.428a1.22 1.22 0 0 0-.3 1.727L16.9 20.481c.408.552 1.2.684 1.77.288a1.22 1.22 0 0 0 .293-1.728L10.696 7.716a1.29 1.29 0 0 0-1.764-.288");
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

.p6y3rlbod {
  fill: var(--svg-color--610467, #610467);
  d: path("M6.095 18.596c-.708 0-1.284.468-1.284 1.152a1.26 1.26 0 0 0 1.284 1.248h11.818a1.26 1.26 0 0 0 1.284-1.248c0-.684-.576-1.152-1.284-1.152z");
}

.ugj5r2bgd {
  stop-color: var(--svg-color--300f39, #300f39);
}

.vu42odb2b {
  d: path("M12.297 6a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.wgrsohb1d {
  fill: var(--svg-color--610467, #610467);
  d: path("M5.37 20.8a1.26 1.26 0 0 0 1.734-.366l3.491-5.321a1.23 1.23 0 0 0-.366-1.716a1.26 1.26 0 0 0-1.733.366l-3.492 5.32A1.23 1.23 0 0 0 5.37 20.8");
}

.zjsj_eomt {
  stop-color: var(--svg-color--610467, #610467);
}

</style>
