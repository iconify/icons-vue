<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGhxp1PdXw" x1="303.46" x2="291.69" y1="-401.7" y2="-386" gradientTransform="matrix(1 0 0 -1 -281.64 -372.94)" gradientUnits="userSpaceOnUse"><stop offset="0" class="k2_l2abgf"/><stop offset="1" class="wp5374bcg"/></linearGradient><linearGradient id="SVGNF68JcOv" x1="300.45" x2="288.67" y1="-403.96" y2="-388.26" href="#SVGhxp1PdXw"/><linearGradient id="SVGvburXdML" x1="298.46" x2="310.24" y1="-401.67" y2="-385.97" gradientTransform="matrix(1 0 0 -1 -281.64 -372.94)" gradientUnits="userSpaceOnUse"><stop offset="0" class="i9apxsjyq"/><stop offset="1" class="zbk47lqvs"/></linearGradient><linearGradient id="SVGFwtjlePY" x1="301.47" x2="313.25" y1="-403.93" y2="-388.23" href="#SVGvburXdML"/></defs><path class="vz5j8lf4y"/><path fill="url(#SVGhxp1PdXw)" class="wzyggbjlx"/><path fill="url(#SVGNF68JcOv)" class="re8m5q0qp"/><path fill="url(#SVGvburXdML)" class="km3h3xy4n"/><path fill="url(#SVGFwtjlePY)" class="vytknsoqq"/><path class="nav0lib5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-changesets-opened" /></template>
<style>
.i9apxsjyq {
  stop-color: var(--svg-color--0089d6, #0089d6);
}

.k2_l2abgf {
  stop-color: var(--svg-color--001b33, #001b33);
}

.km3h3xy4n {
  d: path("M18.68 22.32a7.85 7.85 0 0 1 7.85-7.85h3.93a7.86 7.86 0 0 1-7.85 7.85Z");
}

.nav0lib5e {
  fill: var(--svg-color--08c, #08c);
  d: path("M19.31 19.24a7.84 7.84 0 0 1 0 6.16a7.84 7.84 0 0 1 0-6.16");
}

.re8m5q0qp {
  d: path("M19.94 22.32a7.85 7.85 0 0 1-7.85 7.85h-1.57a7.84 7.84 0 0 1 7.85-7.85Z");
}

.vytknsoqq {
  d: path("M18.68 22.32a7.86 7.86 0 0 0 7.85 7.85h1.57a7.84 7.84 0 0 0-7.85-7.85Z");
}

.vz5j8lf4y {
  fill: var(--svg-color--7db4d3, #7db4d3);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.63Z");
}

.wp5374bcg {
  stop-color: var(--svg-color--006dcc, #006dcc);
}

.wzyggbjlx {
  d: path("M19.94 22.32a7.84 7.84 0 0 0-7.85-7.85H8.16A7.86 7.86 0 0 0 16 22.32Z");
}

.zbk47lqvs {
  stop-color: var(--svg-color--6cf, #6cf);
}

</style>
