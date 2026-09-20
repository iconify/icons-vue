<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGeyciVcvH" x1="0%" x2="100%" y1="100%" y2="0%"><stop offset="0%" class="pkxkyybrw"/><stop offset="100%" class="sl1qm9b9s"/></linearGradient></defs><path fill="url(#SVGeyciVcvH)" class="tmbkaq7lv"/><path class="iht-r9pzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:aws-lambda" /></template>
<style>
.iht-r9pzo {
  fill: var(--svg-color--fff, #fff);
  d: path("M89.624 211.2H49.89l43.945-91.853l19.912 40.992zm7.079-100.63a3.22 3.22 0 0 0-2.887-1.805h-.01a3.2 3.2 0 0 0-2.886 1.82L41.913 213.022a3.203 3.203 0 0 0 2.893 4.58l46.848-.001a3.21 3.21 0 0 0 2.9-1.83l25.65-54.08a3.18 3.18 0 0 0-.016-2.762zM207.985 211.2h-39.477L105.174 78.624a3.21 3.21 0 0 0-2.897-1.824h-25.83l.03-32h50.626l63.042 132.573a3.21 3.21 0 0 0 2.897 1.827h14.943zm3.208-38.4h-16.121L132.03 40.227a3.21 3.21 0 0 0-2.9-1.827H73.273a3.206 3.206 0 0 0-3.208 3.197l-.035 38.4c0 .851.333 1.664.94 2.265c.6.602 1.414.938 2.267.938h27.017l63.337 132.576a3.2 3.2 0 0 0 2.893 1.824h44.709a3.203 3.203 0 0 0 3.207-3.2V176c0-1.766-1.434-3.2-3.207-3.2");
}

.pkxkyybrw {
  stop-color: var(--svg-color--c8511b, #c8511b);
}

.sl1qm9b9s {
  stop-color: var(--svg-color--f90, #f90);
}

.tmbkaq7lv {
  d: path("M0 0h256v256H0z");
}

</style>
