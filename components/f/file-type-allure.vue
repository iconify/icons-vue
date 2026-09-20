<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="SVG6avVPbbn" fill="url(#SVGP98eXdfG)" class="dp031hbps"/></defs><g class="ft5dv1b6b"><g clip-path="url(#SVGkRCCwb7V)" transform="matrix(.8 0 0 .8 3.198 3.2)"><g clip-rule="evenodd" class="d2kvgvbvc"><use href="#SVG6avVPbbn"/><path fill="url(#SVGKTtrecCl)" class="ee5ewvbqv"/><path fill="url(#SVGQkIHBvLp)" class="ck--558kt"/><path fill="url(#SVGLR2Q5bvK)" class="e7hx-yxpp"/><path fill="url(#SVGCf5TPdDy)" class="tdrb0pucy"/><path fill="url(#SVGDfpUvdbi)" class="u1uv2096c"/></g><g clip-path="url(#SVGGccgBdRN)"><use href="#SVG6avVPbbn" clip-rule="evenodd" class="d2kvgvbvc"/></g></g><defs><linearGradient id="SVGP98eXdfG" x1="26.4" x2="28.8" y1="9.6" y2="15.01" gradientUnits="userSpaceOnUse"><stop offset="0" class="zov-qnpum"/><stop offset="1" class="z-wj5t2su"/></linearGradient><linearGradient id="SVGKTtrecCl" x1="26.8" x2="17.8" y1="9.4" y2="3.61" gradientUnits="userSpaceOnUse"><stop offset="0" class="olw50kbdx"/><stop offset="1" class="jwwb_xbwf"/></linearGradient><linearGradient id="SVGQkIHBvLp" x1="3.6" x2="5.4" y1="14.01" y2="24.81" gradientUnits="userSpaceOnUse"><stop offset="0" class="xh53xjbng"/><stop offset="1" class="zj-hb0bfs"/></linearGradient><linearGradient id="SVGLR2Q5bvK" x1="4.8" x2="14.4" y1="22.21" y2="29.21" gradientUnits="userSpaceOnUse"><stop offset="0" class="ykjfm24il"/><stop offset=".96" class="lhkv0xzfh"/><stop offset="1" class="lhkv0xzfh"/></linearGradient><linearGradient id="SVGCf5TPdDy" x1="28.4" x2="22.19" y1="22.18" y2="28.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="anh21-u6s"/><stop offset="1" class="ykd9cjbnf"/></linearGradient><linearGradient id="SVGDfpUvdbi" x1="29.2" x2="30.63" y1="54.43" y2="54.28" gradientUnits="userSpaceOnUse"><stop offset="0" class="ykd9cjbnf"/><stop offset="1" class="ykd9cjbnf"/></linearGradient><clipPath id="SVGkRCCwb7V"><path class="wycjhibbk"/></clipPath><clipPath id="SVGGccgBdRN"><path class="ihvvy5wqv"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-allure" /></template>
<style>
.anh21-u6s {
  stop-color: var(--svg-color--d97706, #d97706);
}

.ck--558kt {
  d: path("M0 16A16 16 0 0 1 16 0a3.6 3.6 0 0 1 0 7.2a8.8 8.8 0 0 0-6.21 15.04a3.603 3.603 0 0 1-5.13 5.06A16.08 16.08 0 0 1 0 16");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dp031hbps {
  d: path("M22.23 4.66a3.6 3.6 0 0 1 5.1.04A16.08 16.08 0 0 1 31.97 16a3.6 3.6 0 1 1-7.2 0c0-2.4-.98-4.61-2.58-6.24a3.6 3.6 0 0 1 .03-5.1z");
}

.e7hx-yxpp {
  d: path("M4.66 22.24a3.6 3.6 0 0 1 5.1-.03a8.87 8.87 0 0 0 6.23 2.59a3.6 3.6 0 0 1 0 7.2c-4.4 0-8.4-1.8-11.3-4.66a3.6 3.6 0 0 1-.03-5.1");
}

.ee5ewvbqv {
  d: path("M12.4 3.6A3.6 3.6 0 0 1 16 0c4.4 0 8.4 1.8 11.29 4.66a3.603 3.603 0 0 1-5.06 5.13A8.87 8.87 0 0 0 16 7.2a3.6 3.6 0 0 1-3.6-3.6");
}

.ft5dv1b6b {
  fill: none;
}

.ihvvy5wqv {
  fill: var(--svg-color--fff, #fff);
  d: path("M24.8 12H32v8h-7.2z");
}

.jwwb_xbwf {
  stop-color: var(--svg-color--dc2626, #dc2626);
}

.lhkv0xzfh {
  stop-color: var(--svg-color--64748b, #64748b);
}

.olw50kbdx {
  stop-color: var(--svg-color--ef4444, #ef4444);
}

.tdrb0pucy {
  d: path("M28.38 12.4a3.6 3.6 0 0 1 3.6 3.6A16 16 0 0 1 16 32a3.6 3.6 0 0 1 0-7.2a8.8 8.8 0 0 0 8.8-8.8a3.6 3.6 0 0 1 3.6-3.6z");
}

.u1uv2096c {
  d: path("M28.38 12.4a3.6 3.6 0 0 1 3.6 3.6v12.4a3.6 3.6 0 1 1-7.2 0V16a3.6 3.6 0 0 1 3.6-3.6");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xh53xjbng {
  stop-color: var(--svg-color--22c55e, #22c55e);
}

.ykd9cjbnf {
  stop-color: var(--svg-color--fbbf24, #fbbf24);
}

.ykjfm24il {
  stop-color: var(--svg-color--94a3b8, #94a3b8);
}

.z-wj5t2su {
  stop-color: var(--svg-color--8b5cf6, #8b5cf6);
}

.zj-hb0bfs {
  stop-color: var(--svg-color--15803d, #15803d);
}

.zov-qnpum {
  stop-color: var(--svg-color--7e22ce, #7e22ce);
}

</style>
