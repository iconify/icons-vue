<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="translate(0 2)"><path class="l3z4llbpw"/><g class="sbmfdz7fg"><path class="u_6746vlj"/><path class="gwzcudbcd"/></g><path class="bvlfwjbig"/><ellipse class="cdla4ybdl"/><ellipse class="ab92eob_c"/><path class="r9s8ji5_d"/><ellipse class="juv3v3cip"/><ellipse class="f5-bkeu0e"/><path class="r5f6l-bqz"/><path class="dsxqysbqs"/><path class="s6nwxzb5r"/><path class="orqijebwt"/><path class="coyt79bvt"/><path class="da4wswbgz"/><path class="lf48nxbnq"/><path class="sc5w8rb7t"/><path class="h1p0wubqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:fire-engine" /></template>
<style>
.ab92eob_c {
  cx: 11.328px;
  cy: 49.915px;
  fill: var(--svg-color--969796, #969796);
  rx: 4.055px;
  ry: 4.151px;
}

.bvlfwjbig {
  fill: var(--svg-color--e3e4e3, #e3e4e3);
  d: path("M18.679 49.563c-.133-4.04-3.37-7.273-7.35-7.273s-7.212 3.234-7.348 7.273z");
}

.cdla4ybdl {
  cx: 11.329px;
  cy: 50px;
  fill: var(--svg-color--243438, #243438);
  rx: 6.256px;
  ry: 6.4px;
}

.coyt79bvt {
  fill: var(--svg-color--4d9dc9, #4d9dc9);
  d: path("M2.414 12.614h12.211v5.418H2.414z");
}

.da4wswbgz {
  fill: var(--svg-color--79bbd9, #79bbd9);
  d: path("M2.414 12.614h6.28v5.418h-6.28z");
}

.dsxqysbqs {
  fill: var(--svg-color--ce2034, #ce2034);
  d: path("M0 39.837h62.66v.906H0z");
}

.f5-bkeu0e {
  cx: 50.789px;
  cy: 49.826px;
  fill: var(--svg-color--969796, #969796);
  rx: 4.056px;
  ry: 4.146px;
}

.gwzcudbcd {
  d: path("M0 18.03h14.14v31.31H0z");
}

.h1p0wubqc {
  fill: var(--svg-color--gray, gray);
  d: path("M20.795 29.13h43.15v1.473h-43.15z");
}

.juv3v3cip {
  cx: 50.789px;
  cy: 49.913px;
  fill: var(--svg-color--243438, #243438);
  rx: 6.256px;
  ry: 6.401px;
}

.l3z4llbpw {
  fill: var(--svg-color--b1203e, #b1203e);
  d: path("M23.627 29.83h14.14v15.521h-14.14z");
}

.lf48nxbnq {
  fill: var(--svg-color--969796, #969796);
  d: path("M23.95 22.01h1.441v8.593H23.95zm5.868 0h1.441v8.593h-1.441zm5.342 0h1.44v8.593h-1.44zm5.03 0h1.441v8.593H40.19zm5.449 0h1.445v8.593h-1.445zm5.297 0h1.435v8.593h-1.435zm5.464 0h1.444v8.593H56.4z");
}

.orqijebwt {
  fill: var(--svg-color--b3b1b3, #b3b1b3);
  d: path("M.932 20.388h6.143v9.634H.932z");
}

.r5f6l-bqz {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 36.919h62.66v2.918H0z");
}

.r9s8ji5_d {
  fill: var(--svg-color--e3e4e3, #e3e4e3);
  d: path("M58.13 49.48c-.134-4.04-3.365-7.275-7.348-7.275c-3.979 0-7.215 3.234-7.348 7.275z");
}

.s6nwxzb5r {
  fill: var(--svg-color--969796, #969796);
  d: path("M.932 20.388h10.397v9.634H.932z");
}

.sbmfdz7fg {
  fill: var(--svg-color--ce2435, #ce2435);
}

.sc5w8rb7t {
  fill: var(--svg-color--cdcbca, #cdcbca);
  d: path("M20.795 22.01h43.15v1.471h-43.15z");
}

.u_6746vlj {
  d: path("M6.53 11h20.571v38.35H6.53zm24.168 4.323h31.961v34.02H30.698z");
}

</style>
