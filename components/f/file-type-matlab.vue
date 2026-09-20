<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGreNHsegy" x1="16.803" x2="15.013" y1="16.631" y2="22.411" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse"><stop offset="0" class="qhi3hac5j"/><stop offset=".23" class="l0sykk29g"/><stop offset=".36" class="pgrs2s85v"/><stop offset=".51" class="ivql9lu8m"/><stop offset=".66" class="rp63etbsb"/><stop offset=".84" class="mdl558vem"/></linearGradient><linearGradient id="SVGuDGJ3bff" x1="29.71" x2="11.71" y1="18.983" y2="14.563" gradientUnits="userSpaceOnUse"><stop offset=".081" class="v-ay6gu7d"/><stop offset=".189" class="o5g85yb7r"/><stop offset=".313" class="hdl32db5j"/><stop offset=".421" class="jmfk15m9m"/><stop offset=".5" class="x4gy31ssg"/><stop offset=".58" class="y3wnhtb0u"/><stop offset=".696" class="pdt6ir45g"/><stop offset=".833" class="qwunf7bba"/><stop offset=".916" class="ar0gsib1j"/></linearGradient></defs><path class="hzx1u4b6y"/><path fill="url(#SVGreNHsegy)" class="w7jqr57dq"/><path fill="url(#SVGuDGJ3bff)" class="yg72hzbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-matlab" /></template>
<style>
.ar0gsib1j {
  stop-color: var(--svg-color--cf3633, #cf3633);
}

.hdl32db5j {
  stop-color: var(--svg-color--f06e3e, #f06e3e);
}

.hzx1u4b6y {
  fill: var(--svg-color--49d, #49d);
  d: path("m2 17.55l7.97-3.22a20.7 20.7 0 0 1 2.72-2.95c.66-.35 1.9-.16 4.17-2.98c2.2-2.75 2.9-5.1 3.93-5.1c1.63 0 2.83 3.52 4.65 8.85A116 116 0 0 0 30 24.12c-1.9-1.77-3.52-3.68-5.37-3.63c-1.72.04-3.63 2.08-5.72 4.7c-1.66 2.1-3.86 3.54-4.72 3.51c0 0-2.22-6.28-4.08-7.3a2.64 2.64 0 0 0-2.39.2L2 17.54Z");
}

.ivql9lu8m {
  stop-color: var(--svg-color--645, #645);
}

.jmfk15m9m {
  stop-color: var(--svg-color--fa8042, #fa8042);
}

.l0sykk29g {
  stop-color: var(--svg-color--523, #523);
}

.mdl558vem {
  stop-color: var(--svg-color--29d, #29d);
}

.o5g85yb7r {
  stop-color: var(--svg-color--de5239, #de5239);
}

.pdt6ir45g {
  stop-color: var(--svg-color--ef6c3e, #ef6c3e);
}

.pgrs2s85v {
  stop-color: var(--svg-color--534, #534);
}

.qhi3hac5j {
  stop-color: var(--svg-color--512, #512);
}

.qwunf7bba {
  stop-color: var(--svg-color--dc4c37, #dc4c37);
}

.rp63etbsb {
  stop-color: var(--svg-color--568, #568);
}

.v-ay6gu7d {
  stop-color: var(--svg-color--c33, #c33);
}

.w7jqr57dq {
  d: path("M19.8 4.02c-.67.9-1.48 2.55-2.94 4.38c-2.27 2.82-3.5 2.63-4.17 2.98a19.7 19.7 0 0 0-2.72 2.95l3.3 2.41c2.8-3.82 4.3-7.96 5.47-10.64a13.6 13.6 0 0 1 1.06-2.08");
}

.x4gy31ssg {
  stop-color: var(--svg-color--fe8643, #fe8643);
}

.y3wnhtb0u {
  stop-color: var(--svg-color--fa7f42, #fa7f42);
}

.yg72hzbwi {
  d: path("M20.8 3.3c-2.18 0-3.67 11.48-11.72 17.89c2.26-.37 4.22 5.24 5.12 7.51c4-.68 7.2-8.33 10.43-8.21c1.85.07 3.47 1.86 5.37 3.63C25.66 15 23.63 3.3 20.8 3.3");
}

</style>
