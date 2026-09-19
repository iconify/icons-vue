<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="lf4uoiblt"/><path class="ikl7ysu_h"/><circle class="qy0n1eb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-laos" /></template>
<style>
.ikl7ysu_h {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v2h64v-2c0-6.075-3.373-11-10-11M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-2H0z");
}

.lf4uoiblt {
  fill: var(--svg-color--2e3192, #2e3192);
  d: path("M0 23h64v18H0z");
}

.qy0n1eb-y {
  cx: 31.979px;
  cy: 31.959px;
  r: 8.291px;
  fill: var(--svg-color--e6e7e8, #e6e7e8);
}

</style>
