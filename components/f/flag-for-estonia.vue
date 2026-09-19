<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ubq_58bja"/><path class="dtf4y2b9t"/><path class="tou9icbzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-estonia" /></template>
<style>
.dtf4y2b9t {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v3h64v-3c0-6.075-3.373-11-10-11");
}

.tou9icbzd {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-3H0z");
}

.ubq_58bja {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M0 24h64v16H0z");
}

</style>
