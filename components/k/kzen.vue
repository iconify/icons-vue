<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGD8ZAocSd)" class="w_kw0uaib"/><path fill="url(#SVGai7pCdce)" class="i1xclccmq"/><path class="gzjbi7u9u"/><defs><linearGradient id="SVGD8ZAocSd" x1="16.939" x2="6.927" y1="4.125" y2="19.714" gradientUnits="userSpaceOnUse"><stop offset=".16" class="xzkl2dbcs"/><stop offset=".59" class="z3ptbacko"/><stop offset="1" class="p_c3p5pmw"/></linearGradient><linearGradient id="SVGai7pCdce" x1="14.647" x2="12.33" y1="3.562" y2="7.379" gradientUnits="userSpaceOnUse"><stop offset=".07" class="oar3xy26p"/><stop offset="1" class="sivdrfbzo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kzen" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gzjbi7u9u {
  fill: var(--svg-color--181b1e, #181b1e);
  d: path("M10.411 6.706H12v10.059h-1.588zm6.771-2.647l-.937-.985L16.187 3a14.54 14.54 0 0 0-3.129 8.958c0 3.43 1.191 6.58 3.177 9.042l1.058-1.048a13.04 13.04 0 0 1-2.694-7.994c0-2.954.958-5.729 2.583-7.9");
}

.i1xclccmq {
  d: path("M20.47 12a8.47 8.47 0 1 0-16.94 0a8.47 8.47 0 0 0 16.94 0");
}

.oar3xy26p {
  stop-color: var(--svg-color--ff5353, #ff5353);
}

.p_c3p5pmw {
  stop-color: var(--svg-color--c50101, #c50101);
}

.sivdrfbzo {
  stop-color: var(--svg-color--c50101, #c50101);
  stop-opacity: 0;
}

.w_kw0uaib {
  d: path("M12 20.47a8.47 8.47 0 1 0 0-16.94a8.47 8.47 0 0 0 0 16.94");
}

.xzkl2dbcs {
  stop-color: var(--svg-color--ffa3a3, #ffa3a3);
}

.z3ptbacko {
  stop-color: var(--svg-color--c50000, #c50000);
}

</style>
