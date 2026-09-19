<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zz_61l_4x"/><path class="vy68gabdc"/><path class="hbpnxvb0m"/><path class="q11avkbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-mauritius" /></template>
<style>
.hbpnxvb0m {
  fill: var(--svg-color--699635, #699635);
  d: path("M6.6 48c5.3 8.4 14.7 14 25.4 14s20.1-5.6 25.4-14z");
}

.q11avkbzl {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M57.4 48c2.9-4.6 4.6-10.1 4.6-16H2c0 5.9 1.7 11.4 4.6 16z");
}

.vy68gabdc {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M6.6 16C3.7 20.6 2 26.1 2 32h60c0-5.9-1.7-11.4-4.6-16z");
}

.zz_61l_4x {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2C21.3 2 11.9 7.6 6.6 16h50.7C52.1 7.6 42.7 2 32 2");
}

</style>
