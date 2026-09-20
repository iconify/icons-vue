<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wvxh5-bzu"/><path class="vqh4zmbrb"/><path class="m25r5eyhm"/><ellipse class="r1-isbbyv"/><ellipse class="l14oska9u"/><path class="nc9h86buv"/><path class="m3m2qib-y"/><path class="arxq0vjlr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:jar" /></template>
<style>
.arxq0vjlr {
  fill: var(--svg-color--fff, #fff);
  d: path("M10 31a1 1 0 0 1-1-1V14a1 1 0 1 1 2 0v16a1 1 0 0 1-1 1");
}

.l14oska9u {
  cx: 18px;
  cy: 30.5px;
  fill: var(--svg-color--aeb3b2, #aeb3b2);
  rx: 11px;
  ry: 3px;
}

.m25r5eyhm {
  fill: var(--svg-color--f19020, #f19020);
  d: path("M7 4h22v2.8H7z");
}

.m3m2qib-y {
  fill: var(--svg-color--aeb3b2, #aeb3b2);
  d: path("M18 12c-1.145 0-5.129-.07-8.335-.974a.5.5 0 1 1 .271-.963c3.083.87 6.952.937 8.064.937s4.981-.067 8.063-.937a.501.501 0 0 1 .271.963C23.129 11.93 19.145 12 18 12");
}

.nc9h86buv {
  fill: var(--svg-color--f19020, #f19020);
  d: path("M10.465 4c1.099-.582 4.053-1 7.535-1s6.436.418 7.535 1c.296-.157.465-.324.465-.5c0-.828-3.582-1.5-8-1.5s-8 .672-8 1.5c0 .176.169.343.465.5");
}

.r1-isbbyv {
  cx: 18px;
  cy: 4px;
  fill: var(--svg-color--f9ca55, #f9ca55);
  rx: 11px;
  ry: 3px;
}

.vqh4zmbrb {
  fill: var(--svg-color--f19020, #f19020);
  d: path("M29 6.8c0 1.657-4.925 3.2-11 3.2S7 8.457 7 6.8S11.925 4 18 4s11 1.143 11 2.8");
}

.wvxh5-bzu {
  fill: var(--svg-color--c4c9c8, #c4c9c8);
  d: path("M8 8c0 .64.254 1.254.707 1.707a.256.256 0 0 1-.1.424l-.556.185A3 3 0 0 0 6 13.162v18.451q0 .003.004.004c0 .007-.004.014-.004.021c0 1.796 5.373 3.252 12 3.252s12-1.456 12-3.252l-.004-.021a.004.004 0 0 0 .004-.004V13.162a3 3 0 0 0-2.051-2.846l-.795-.265a.1.1 0 0 1-.04-.165l.178-.178A2.42 2.42 0 0 0 28 8z");
}

</style>
