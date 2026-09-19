<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pmy273bui"/><path class="d6g92ibuw"/><circle class="ivg48e7_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-laos" /></template>
<style>
.d6g92ibuw {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M57.4 16C52.1 7.6 42.7 2 32 2S11.9 7.6 6.6 16zM6.6 48c5.3 8.4 14.7 14 25.4 14s20.1-5.6 25.4-14z");
}

.ivg48e7_b {
  cx: 32px;
  cy: 32px;
  r: 10px;
  fill: var(--svg-color--fff, #fff);
}

.pmy273bui {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M2 32c0 5.9 1.7 11.4 4.6 16h50.7c2.9-4.6 4.6-10.1 4.6-16s-1.7-11.4-4.6-16H6.6C3.7 20.6 2 26.1 2 32");
}

</style>
