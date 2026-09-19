<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="t76_qd-2z"/><path class="xmwf8-bmx"/><path class="gjp-xhbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-luxembourg" /></template>
<style>
.gjp-xhbgq {
  fill: var(--svg-color--28a3ce, #28a3ce);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-4H0z");
}

.t76_qd-2z {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 25h64v14H0z");
}

.xmwf8-bmx {
  fill: var(--svg-color--c32129, #c32129);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v4h64v-4c0-6.075-3.373-11-10-11");
}

</style>
