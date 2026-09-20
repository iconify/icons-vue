<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nrn36fb7v"/><circle class="qjpgfccgq"/><path class="umouuybqo"/><path class="otx8q0r5w"/><path class="wd3kil02w"/><path class="o73u4_bfi"/><path class="dj8rhobhn"/><ellipse class="opv7x-qaw"/><ellipse transform="rotate(-74.365 34.047 9.981)" class="hbwamurmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:alembic" /></template>
<style>
.dj8rhobhn {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("M29 23a1 1 0 0 1-1 1H3a1 1 0 1 1 0-2h25a1 1 0 0 1 1 1");
}

.hbwamurmg {
  cx: 34.047px;
  cy: 9.982px;
  fill: var(--svg-color--aab8c2, #aab8c2);
  rx: 1.341px;
  ry: 0.974px;
}

.nrn36fb7v {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M16 34.375a1 1 0 1 1-2 0V26a1 1 0 1 1 2 0z");
}

.o73u4_bfi {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M19.006 2.266S32.36 6.948 33.778 7.404c3.725 1.199 2.184 5.224-.385 4.582c-5.083-1.271-14.387-4.068-15.415-4.068s1.028-5.652 1.028-5.652");
}

.opv7x-qaw {
  cx: 15.41px;
  cy: 16.139px;
  fill: var(--svg-color--3b94d9, #3b94d9);
  rx: 11.818px;
  ry: 1.629px;
}

.otx8q0r5w {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M30 24a2 2 0 0 1-2 2H3a2 2 0 0 1 0-4h25a2 2 0 0 1 2 2");
}

.qjpgfccgq {
  cx: 15.41px;
  cy: 15.625px;
  r: 13.873px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.umouuybqo {
  fill: var(--svg-color--50a5e6, #50a5e6);
  d: path("M3.592 16.139c.232 6.334 5.427 11.402 11.818 11.402s11.586-5.068 11.818-11.402z");
}

.wd3kil02w {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M2.622 35.207a.999.999 0 1 1-1.883-.673l3.317-9.262a1 1 0 1 1 1.883.673zm25.757 0a1 1 0 0 0 1.882-.673l-3.359-9.345a1 1 0 1 0-1.882.672z");
}

</style>
