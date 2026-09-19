<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="kfs7nwd-w"/><path class="xgrwu_xlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:check-mark-button" /></template>
<style>
.kfs7nwd-w {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4bd37b, #4bd37b);
}

.xgrwu_xlq {
  fill: var(--svg-color--fff, #fff);
  d: path("M46 14L25 35.6l-7-7.2l-7 7.2L25 50l28-28.8z");
}

</style>
