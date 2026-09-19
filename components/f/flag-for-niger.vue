<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q04a6rbeo"/><path class="f3mhcexpn"/><path class="hlv7oibbb"/><circle class="nmya-1jcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-niger" /></template>
<style>
.f3mhcexpn {
  fill: var(--svg-color--e05206, #e05206);
  d: path("M54 10H10C3.373 10 0 14.925 0 21v2h64v-2c0-6.075-3.373-11-10-11");
}

.hlv7oibbb {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M0 43c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11v-2H0z");
}

.nmya-1jcl {
  cx: 31.979px;
  cy: 31.959px;
  r: 8.291px;
  fill: var(--svg-color--e05206, #e05206);
}

.q04a6rbeo {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 23h64v18H0z");
}

</style>
