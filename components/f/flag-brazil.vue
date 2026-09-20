<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="rey0tebpg"/><path class="w55nzqori"/><circle class="ny824nbgq"/><path class="m9l2f9bry"/><path class="e6uxn-b2t"/><path class="esqx-ub0w"/><path class="oa1v6yokg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-brazil" /></template>
<style>
.e6uxn-b2t {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M12 18.233h1v1h-1zm1 2h1v1h-1z");
}

.esqx-ub0w {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M15 18.233h1v1h-1zm2 1h1v1h-1zm4 2h1v1h-1zm-3 1h1v1h-1zm3-6h1v1h-1z");
}

.m9l2f9bry {
  fill: var(--svg-color--cbe9d4, #cbe9d4);
  d: path("M12.277 14.887a6.4 6.4 0 0 0-.672 2.023c3.995-.29 9.417 1.891 11.744 4.595c.402-.604.7-1.28.883-2.004c-2.872-2.808-7.917-4.63-11.955-4.614");
}

.ny824nbgq {
  cx: 17.976px;
  cy: 17.924px;
  r: 6.458px;
  fill: var(--svg-color--002776, #002776);
}

.oa1v6yokg {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M19 20.233h1v1h-1z");
}

.rey0tebpg {
  fill: var(--svg-color--009b3a, #009b3a);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.w55nzqori {
  fill: var(--svg-color--fedf01, #fedf01);
  d: path("M32.728 18L18 29.124L3.272 18L18 6.875z");
}

</style>
