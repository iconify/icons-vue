<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wmkfdhb2l"/><path class="vtw1v3wei"/><path class="q29__vbnc"/><path class="zvd32gpit"/><path class="jvw8bnzus"/><circle class="vzc-s7-lf"/><path class="sfg30rbdv"/><path class="in431lamb"/><path class="jpnix05-d"/><path class="m26by6bca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:banana" /></template>
<style>
.in431lamb {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M26 19c3 0 8 3 7 9s-5 7-7 7h-2c-2 0-1-1 0-2s4 0 4-6c0-3-4-7-6-7c0 0 2-1 4-1");
}

.jpnix05-d {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M17 21c3 0 5 1 3 3c-1.581 1.581-6 5-10 6s-8 1-5-1s9.764-8 12-8");
}

.jvw8bnzus {
  fill: var(--svg-color--a6d388, #a6d388);
  d: path("M26 35h-4c-2 0-3 1-4 1s-2-2 0-2s4 0 5-1s5 2 3 2");
}

.m26by6bca {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M2 31c1 0 1 0 1 .667C3 32.333 3 33 2 33s-1-1.333-1-1.333S1 31 2 31");
}

.q29__vbnc {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M22 20c-.296.592 1.167-3.833-3-6c-1.984-1.032-10 1-4 1c3 0 4 2 2 4a2.9 2.9 0 0 0-.622.912c-.417.346-.873.709-1.378 1.088c-2.263 1.697-5.84 4.227-10 7c-3 2-4 3-4 4c0 3 9 3 14 1s10-7 10-7l4-4c-3-4-7-2-7-2");
}

.sfg30rbdv {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M32.208 28S28 35 26 35h-4c-2 0 0-1 1-2s5 0 5-6c0-3 4.208 1 4.208 1");
}

.vtw1v3wei {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M31 8c0 3-1 9-4 13s-7 5-4 1s5-7 6-11s2-7 2-3");
}

.vzc-s7-lf {
  cx: 18px;
  cy: 35px;
  r: 1px;
  fill: var(--svg-color--3e721d, #3e721d);
}

.wmkfdhb2l {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M28 2c2.684-1.342 5 4 3 13c-1.106 4.977-5 9-9 12s-11-1-7-5s8-7 10-13c1.304-3.912 1-6 3-7");
}

.zvd32gpit {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M22 20s1.792-4.729-3-7c-4.042-1.916-8-1-11 1s-2 4-3 5s1 2 3 0s8.316-4.895 11-4c3 1 2 2.999 3 5");
}

</style>
