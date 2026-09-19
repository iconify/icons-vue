<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="js8d5ublq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:letter-m" /></template>
<style>
.bgatx5byk {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

.js8d5ublq {
  fill: var(--svg-color--fff, #fff);
  d: path("M37.3 17.5H46v29h-5.7V22.1l-5.5 24.4H29l-5.5-24.4v24.4H18v-29h8.8l5.3 22.8z");
}

</style>
