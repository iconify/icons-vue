<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w5_i-rbfs"/><path class="x2q5uyizw"/><path class="se8lkhr7b"/><path class="nc43d3b6a"/><path class="t_ie5cb7x"/><path class="rek25s3lv"/><path class="vp7usjbll"/><path class="z0az8nhyk"/><path class="junbjcb0g"/><path class="qkrzl_bol"/><path class="oys19uoej"/><path class="dl_ymgb-p"/><path class="dlw-cgnfb"/><path class="xo1b04bei"/><path class="v-ih7bbwh"/><circle class="i6ko01b_h"/><circle class="rl_blm2wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bento-box" /></template>
<style>
.dl_ymgb-p {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M5 8c-1.2-1.6 1-5 6-5c1 1-3 9-6 5");
}

.dlw-cgnfb {
  fill: var(--svg-color--b2c2cc, #b2c2cc);
  d: path("M6 27a.999.999 0 0 1-.707-1.707l1-1a.999.999 0 1 1 1.414 1.414l-1 1A1 1 0 0 1 6 27m12.417.499a1 1 0 0 1-.707-.293l-1-1a1 1 0 1 1 1.415-1.414l1 1a.999.999 0 0 1-.708 1.707m-6.167-4.291c-.255 0-.511-.098-.707-.292l-.459-.458a1 1 0 1 1 1.413-1.416l.459.458a1 1 0 0 1-.706 1.708");
}

.i6ko01b_h {
  cx: 12px;
  cy: 26px;
  r: 1px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.junbjcb0g {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M23.113 11.536c-1.562.535-2.965.568-3.133.076l-.305-.891c-.169-.492.962-1.324 2.522-1.858l4.242-1.45c1.562-.534 2.964-.567 3.133-.075l.304.89c.169.493-.961 1.325-2.523 1.858z");
}

.nc43d3b6a {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M14 13a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2zm19 0a2 2 0 0 1-2 2H18a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2z");
}

.oys19uoej {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M6.584 7.784c3.739-1.737 3.293 3.763 2.672 6.698c-1.956-.414-7.206-4.59-2.672-6.698");
}

.qkrzl_bol {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M6.442 7.873c.373-4.106 4.907-.961 7.135 1.049c-1.34 1.485-7.586 3.93-7.135-1.049");
}

.rek25s3lv {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M33 27a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2z");
}

.rl_blm2wh {
  cx: 20px;
  cy: 22px;
  r: 1px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.se8lkhr7b {
  fill: var(--svg-color--be1931, #be1931);
  d: path("M22 27a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2zm11-8a2 2 0 0 0-2-2h-5a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2zM16 4a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H18a2 2 0 0 1-2-2zm-2 9a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2z");
}

.t_ie5cb7x {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M22 27a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h15a2 2 0 0 1 2 2z");
}

.v-ih7bbwh {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M32.149 21.412a2 2 0 0 1-.257 2.816l-2.305 1.921a2 2 0 0 1-2.816-.257l-1.921-2.305a2 2 0 0 1 .257-2.816l2.305-1.921a2 2 0 0 1 2.816.257z");
}

.vp7usjbll {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M27.015 9.24c1.315 1.478 1.908 3.098 1.322 3.619l-1.059.941c-.585.522-2.126-.255-3.44-1.733l-3.571-4.013c-1.314-1.479-1.907-3.099-1.321-3.62l1.059-.941c.586-.521 2.124.255 3.438 1.733z");
}

.w5_i-rbfs {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M31 0H5a4 4 0 0 0-4 4v28a4 4 0 0 0 4 4h26a4 4 0 0 0 4-4V4a4 4 0 0 0-4-4");
}

.x2q5uyizw {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M14 11a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h1a4 4 0 0 1 4 4z");
}

.xo1b04bei {
  fill: var(--svg-color--b26304, #b26304);
  d: path("M32.149 23.412a2 2 0 0 1-.257 2.816l-2.305 1.921a2 2 0 0 1-2.816-.257l-1.921-2.305a2 2 0 0 1 .257-2.816l2.305-1.921a2 2 0 0 1 2.816.257z");
}

.z0az8nhyk {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M22.28 11.076c-.598 1.539-1.477 2.633-1.961 2.444l-.877-.341c-.485-.188-.393-1.588.205-3.126l1.625-4.178c.599-1.538 1.477-2.632 1.962-2.444l.876.341c.485.188.394 1.588-.205 3.126z");
}

</style>
