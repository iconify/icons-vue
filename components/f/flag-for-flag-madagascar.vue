<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hif9sqbwg"/><path class="la2ls8bzv"/><path class="rafc4xbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-madagascar" /></template>
<style>
.hif9sqbwg {
  fill: var(--svg-color--156d08, #156d08);
  d: path("M4 43c0 6.075 1.373 11 8 11h42c6.627 0 10-4.925 10-11V32H2z");
}

.la2ls8bzv {
  fill: var(--svg-color--c32129, #c32129);
  d: path("M54 10H12C5.373 10 1 14.925 1 21v12h63V21c0-6.075-3.373-11-10-11");
}

.rafc4xbvs {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12V10z");
}

</style>
