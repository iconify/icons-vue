<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<circle class="izg-497iq"/><circle class="m872hjyxh"/><path class="do63ho_ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:green-circle" /></template>
<style>
.do63ho_ls {
  fill: var(--svg-color--aed581, #aed581);
  d: path("M23.93 29.7c4.5-7.1 14.1-13 24.1-14.8c2.5-.4 5-.6 7.1.2c1.6.6 2.9 2.1 2 3.8c-.7 1.4-2.6 2-4.1 2.5a44.64 44.64 0 0 0-23 17.4c-2 3-5 11.3-8.7 9.2c-3.9-2.3-3.1-9.5 2.6-18.3");
}

.izg-497iq {
  cx: 63.93px;
  cy: 64px;
  r: 60px;
  fill: var(--svg-color--689f38, #689f38);
}

.m872hjyxh {
  cx: 60.03px;
  cy: 63.1px;
  r: 56.1px;
  fill: var(--svg-color--7cb342, #7cb342);
}

</style>
