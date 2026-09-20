<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jpx4dbcpt"/><path class="jymlrdbhz"/><circle class="ny824nbgq"/><path class="eea0e4elf"/><path class="aay2ci9rt"/><path class="meu1tnbik"/><path class="bkj2ccbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-brazil" /></template>
<style>
.aay2ci9rt {
  fill: var(--svg-color--88c9f9, #88C9F9);
  d: path("M12 18.233h1v1h-1zm1 2h1v1h-1z");
}

.bkj2ccbfx {
  fill: var(--svg-color--3b88c3, #3B88C3);
  d: path("M19 20.233h1v1h-1z");
}

.eea0e4elf {
  fill: var(--svg-color--cbe9d4, #CBE9D4);
  d: path("M12.277 14.887a6.406 6.406 0 0 0-.672 2.023c3.995-.29 9.417 1.891 11.744 4.595c.402-.604.7-1.28.883-2.004c-2.872-2.808-7.917-4.63-11.955-4.614z");
}

.jpx4dbcpt {
  fill: var(--svg-color--009b3a, #009B3A);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v18z");
}

.jymlrdbhz {
  fill: var(--svg-color--fedf01, #FEDF01);
  d: path("M32.728 18L18 29.124L3.272 18L18 6.875z");
}

.meu1tnbik {
  fill: var(--svg-color--55acee, #55ACEE);
  d: path("M15 18.233h1v1h-1zm2 1h1v1h-1zm4 2h1v1h-1zm-3 1h1v1h-1zm3-6h1v1h-1z");
}

.ny824nbgq {
  fill: var(--svg-color--002776, #002776);
  cx: 17.976px;
  cy: 17.924px;
  r: 6.458px;
}

</style>
