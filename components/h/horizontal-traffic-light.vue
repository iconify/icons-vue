<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zwy30wb3n"/><path class="qebotbb8v"/><circle class="xo5blw24s"/><circle class="y-kibyknq"/><circle class="owc5gpbqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:horizontal-traffic-light" /></template>
<style>
.owc5gpbqp {
  cx: 13.743px;
  cy: 33.31px;
  r: 8.121px;
  fill: var(--svg-color--4fba80, #4fba80);
}

.qebotbb8v {
  fill: var(--svg-color--1f2e35, #1f2e35);
  d: path("M15.279 45.87c-6.937 0-12.562-5.625-12.562-12.565c0-6.937 5.624-12.564 12.562-12.564h33.472c6.936 0 12.563 5.626 12.563 12.564c0 6.94-5.627 12.565-12.563 12.565z");
}

.xo5blw24s {
  cx: 50.35px;
  cy: 33.31px;
  r: 8.121px;
  fill: var(--svg-color--ec1c24, #ec1c24);
}

.y-kibyknq {
  cx: 32.02px;
  cy: 33.31px;
  r: 8.121px;
  fill: var(--svg-color--ffdd15, #ffdd15);
}

.zwy30wb3n {
  fill: var(--svg-color--bfc7cb, #bfc7cb);
  d: path("M13.721 47.999C6.146 47.999 0 41.375 0 33.203s6.146-14.797 13.721-14.797H50.28c7.577 0 13.721 6.624 13.721 14.797C64.001 41.375 57.857 48 50.28 48z");
}

</style>
