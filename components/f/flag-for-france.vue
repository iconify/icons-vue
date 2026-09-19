<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zzyf9-41q"/><path class="oak04b3jg"/><path class="cfqr_ccbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-france" /></template>
<style>
.cfqr_ccbq {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M52 10H42v44h12c6.627 0 10-4.925 10-11V21c0-6.076-.042-11-12-11");
}

.oak04b3jg {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12V10z");
}

.zzyf9-41q {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M22 10h20v44H22z");
}

</style>
