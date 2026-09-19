<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uvy_l3b5i"/><path class="fnl-we-jy"/><path class="ivvhgh-6y"/><path class="alo7wou8m"/><path class="ldduf345s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-faroe-islands" /></template>
<style>
.alo7wou8m {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M20 10h7v44h-7z");
}

.fnl-we-jy {
  fill: var(--svg-color--003f87, #003f87);
  d: path("M18 10h11v44H18z");
}

.ivvhgh-6y {
  fill: var(--svg-color--003f87, #003f87);
  d: path("M0 27h64v10H0z");
}

.ldduf345s {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M0 29h64v6H0z");
}

.uvy_l3b5i {
  fill: var(--svg-color--eaeaea, #eaeaea);
  d: path("M64 43c0 6.075-3.373 11-10 11H10C3.373 54 0 49.075 0 43V21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11z");
}

</style>
