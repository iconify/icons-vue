<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n2cbeqw8g"/><path class="vptb104bk"/><path class="li36trbfs"/><path class="fu19npbvs"/><path class="adppjdbmd"/><path class="f1wlg9b3b"/><path fill="url(#SVGdtDFddMb)" class="w54zptb_v"/><defs><linearGradient id="SVGdtDFddMb" x1="7.775" x2="20.049" y1="13.585" y2="13.585" gradientUnits="userSpaceOnUse"><stop offset=".35" class="tl5vlfl9e"/><stop offset=".76" class="i2k1v2mfs"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kom" /></template>
<style>
.adppjdbmd {
  fill: var(--svg-color--2b6def, #2b6def);
  d: path("m6.375 18.187l-2.25 1.407L6.369 21l2.256-1.406zm11.25-9.562l-2.25 1.406l2.25 1.406l2.25-1.406z");
}

.f1wlg9b3b {
  fill: var(--svg-color--2891f9, #2891f9);
  d: path("M6.375 9.446L17.625 3v2.773L6.375 12z");
}

.ft5dv1b6b {
  fill: none;
}

.fu19npbvs {
  fill: var(--svg-color--2bbdf7, #2bbdf7);
  d: path("M19.875 4.322L17.625 3v5.906l2.25 1.125zm-11.25-.27L6.375 3v15.547l2.25 1.052z");
}

.i2k1v2mfs {
  stop-color: var(--svg-color--2bbcf7, #2bbcf7);
}

.li36trbfs {
  fill: var(--svg-color--2891f9, #2891f9);
  d: path("M4.125 4.052L6.375 3v15.547L4.125 19.6zm11.25.326L17.625 3v5.946l-2.25 1.085z");
}

.n2cbeqw8g {
  fill: var(--svg-color--2891f9, #2891f9);
  d: path("M15.375 15.015v-1.89L17.625 12l.056 4.185z");
}

.tl5vlfl9e {
  stop-color: var(--svg-color--2b6def, #2b6def);
}

.vptb104bk {
  fill: var(--svg-color--2b6def, #2b6def);
  d: path("m10.712 12.022l5.26-3.06l.309-3.122l-8.258 3.657v2.525zM17.642 21l2.233-1.407l-11.272-6.502L6.1 14.385z");
}

.w54zptb_v {
  d: path("m6.375 11.999l13.5 7.594v-6.469l-2.25-1.125v3.937l-9.017-5.191z");
}

</style>
