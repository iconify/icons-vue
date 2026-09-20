<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="t3do-efnj"/><circle class="m647rpbgt"/><path class="nf1zf9bbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:blue-circle" /></template>
<style>
.m647rpbgt {
  cx: 60.03px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--1976d2, #1976d2);
}

.nf1zf9bbi {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.93 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5a44.64 44.64 0 0 0-23 17.4c-2 3-5 11.3-8.7 9.2c-3.9-2.3-3.1-9.5 2.6-18.3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.t3do-efnj {
  cx: 63.93px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--0d47a1, #0d47a1);
}

</style>
