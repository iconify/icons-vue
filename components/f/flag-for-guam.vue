<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pnklixw7b"/><path class="hmdioobgx"/><path id="SVGdFciccnU" class="bb6ch_b1k"/><use href="#SVGdFciccnU"/><path class="fk0j-19st"/><path class="cs6l9mbww"/><path class="he_-ipoxw"/><path class="yf42w7bjy"/><path class="g-996vbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-guam" /></template>
<style>
.bb6ch_b1k {
  fill: var(--svg-color--b4d7ee, #b4d7ee);
  d: path("M42 32c0 8.8-10 16-10 16s-10-7.2-10-16s10-16 10-16s10 7.2 10 16");
}

.cs6l9mbww {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M24 32c0 2.8 1.2 5.3 2.6 7.4c5.1-1.4 9.6-4 13.4-7.4z");
}

.fk0j-19st {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M26.6 39.4C29 42.8 32 45 32 45s8-5.8 8-13c-3.8 3.4-8.3 6-13.4 7.4");
}

.g-996vbic {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("m32 22.2l2.5-2.2l-.8 3.1l3.3.9l-3.3.9l.8 3.1l-2.5-2.2l-2.5 2.2l.8-3.1L27 24l3.3-.9l-.8-3.1z");
}

.he_-ipoxw {
  fill: var(--svg-color--fff, #fff);
  d: path("M28 30v4h4z");
}

.hmdioobgx {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M14 8h36c-5-3.8-11.2-6-18-6S19 4.2 14 8m18 54c6.8 0 13-2.2 18-6H14c5 3.8 11.2 6 18 6m11.5-30C43.5 42.2 32 50.5 32 50.5S20.5 42.2 20.5 32S32 13.5 32 13.5S43.5 21.8 43.5 32");
}

.pnklixw7b {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M2 32c0 9.8 4.7 18.5 12 24h36c7.3-5.5 12-14.2 12-24S57.3 13.5 50 8H14C6.7 13.5 2 22.2 2 32");
}

.yf42w7bjy {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M34.9 39c-3.8-6.8-3.3-13.7-3.3-14l.8.1c0 .1-.5 6.9 3.1 13.4z");
}

</style>
