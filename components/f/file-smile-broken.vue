<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="iumob5e9e"/><path class="wcz3c02rs"/><path class="df4ydac7s"/><ellipse class="y1xu7ibpb"/><ellipse class="mo93ri__q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-smile-broken" /></template>
<style>
.df4ydac7s {
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 10V14C2 17.7712 2 19.6569 3.17157 20.8284C4.34315 22 6.22876 22 10 22H14C17.7712 22 19.6569 22 20.8284 20.8284C21.4816 20.1752 21.7706 19.3001 21.8985 18M22 14V13.5629C22 11.8083 22 10.931 21.654 10.1541C21.308 9.3772 20.6559 8.79032 19.3517 7.61654L15.3929 4.05365C14.2651 3.03857 13.7012 2.53104 13.0092 2.26552C12.3173 2 11.5548 2 10.0298 2C6.23869 2 4.34315 2 3.17157 3.17157C2.51839 3.82475 2.22937 4.69989 2.10149 6");
}

.iumob5e9e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 2.2627V5.0003C13 7.35732 13 8.53583 13.7322 9.26806C14.4645 10.0003 15.643 10.0003 18 10.0003H21.58");
}

.mo93ri__q {
  cx: 7px;
  cy: 14.5px;
  rx: 0.5px;
  ry: 1px;
}

.pr52f_b5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
}

.wcz3c02rs {
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 17.5C10.8167 18.7111 13.1833 18.7111 15 17.5");
}

.y1xu7ibpb {
  cx: 17px;
  cy: 14.5px;
  rx: 0.5px;
  ry: 1px;
}

</style>
