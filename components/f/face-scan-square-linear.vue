<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="so69kfbvn"/><path class="qaz3lvb_a"/><path class="etjnuzbeh"/><path class="jzbgmtzzc"/><path class="shnnyvbiu"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:face-scan-square-linear" /></template>
<style>
.etjnuzbeh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 22C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14");
}

.jzbgmtzzc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 2C6.22876 2 4.34315 2 3.17157 3.17157C2 4.34315 2 6.22876 2 10");
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.qaz3lvb_a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M22 14C22 17.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22");
}

.shnnyvbiu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 2C17.7712 2 19.6569 2 20.8284 3.17157C22 4.34315 22 6.22876 22 10");
}

.so69kfbvn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 16C9.85038 16.6303 10.8846 17 12 17C13.1154 17 14.1496 16.6303 15 16");
}

.wbw_ixbrw {
  d: path("M15.5 10.5C15.5 11.0523 15.2761 11.5 15 11.5C14.7239 11.5 14.5 11.0523 14.5 10.5C14.5 9.94772 14.7239 9.5 15 9.5C15.2761 9.5 15.5 9.94772 15.5 10.5Z");
}

.yad62e0rw {
  cx: 9px;
  cy: 10.5px;
  rx: 0.5px;
  ry: 1px;
}

</style>
