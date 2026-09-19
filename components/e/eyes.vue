<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xvzgv5-dw"/><path class="z4a_60bin"/><path class="yyvkqcbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:eyes" /></template>
<style>
.xvzgv5-dw {
  fill: var(--svg-color--dde8e3, #dde8e3);
  d: path("M2 31.4C2 40.2 5.7 53 17 53s15-12.8 15-21.6c0-27.2-30-27.2-30 0m30 0C32 40.2 35.7 53 47 53s15-12.8 15-21.6c0-27.2-30-27.2-30 0");
}

.yyvkqcbtb {
  fill: var(--svg-color--493b30, #493b30);
  d: path("M2.8 32.2c0 6.2 4.4 11 9.7 11c5.4 0 9.7-4.8 9.7-11c0-15.2-19.4-15.2-19.4 0m30 0c0 6.2 4.4 11 9.7 11c5.4 0 9.7-4.8 9.7-11c0-15.2-19.4-15.2-19.4 0");
}

.z4a_60bin {
  fill: var(--svg-color--fff, #fff);
  d: path("M2.8 32.1c0 7.6 2.4 19.3 12 19.3s12-11.8 12-19.3c-.1-26-24-26-24 0m30 0c0 7.6 2.4 19.3 12 19.3s12-11.8 12-19.3c-.1-26-24-26-24 0");
}

</style>
