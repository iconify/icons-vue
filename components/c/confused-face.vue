<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mb4__7bhf"/><ellipse class="lmj63bhww"/><path class="ucfy-ztoi"/><ellipse class="aphwjebgd"/><ellipse class="otttnnboc"/><path class="supicr7sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:confused-face" /></template>
<style>
.aphwjebgd {
  cx: 20.649px;
  cy: 27.19px;
  fill: var(--svg-color--fff, #fff);
  rx: 6.432px;
  ry: 9.631px;
}

.lmj63bhww {
  cx: 42.16px;
  cy: 27.514px;
  fill: var(--svg-color--fff, #fff);
  rx: 6.432px;
  ry: 9.631px;
}

.mb4__7bhf {
  fill: var(--svg-color--fbbf67, #fbbf67);
  d: path("M63.29 31.941c0 17.476-14.167 31.645-31.645 31.645c-17.48 0-31.649-14.169-31.649-31.645C-.004 14.461 14.165.292 31.645.292c17.478 0 31.645 14.169 31.645 31.649");
}

.otttnnboc {
  cx: 20.649px;
  cy: 27.19px;
  fill: var(--svg-color--25333a, #25333a);
  rx: 4.161px;
  ry: 5.05px;
}

.supicr7sb {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M45.04 42.849c-10.166-1.612-21.15 1.373-30.25 5.839c-2.02.993-.592 4.192 1.442 3.195c8.56-4.201 18.866-7.07 28.44-5.55c2.234.355 2.591-3.131.366-3.484");
}

.ucfy-ztoi {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M37.998 27.514c0 2.787 1.86 5.05 4.16 5.05c2.301 0 4.161-2.259 4.161-5.05c0-2.787-1.86-5.05-4.161-5.05s-4.16 2.26-4.16 5.05");
}

</style>
