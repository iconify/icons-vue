<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="n8dhie24t"/><path class="buk2b0b2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-ukraine" /></template>
<style>
.buk2b0b2e {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11V32H0z");
}

.n8dhie24t {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v11h64V21c0-6.075-3.373-11-10-11");
}

</style>
