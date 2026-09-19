<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q8dsofbns"/><path class="rfevtxe1e"/><path class="b2qzmwbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-sweden" /></template>
<style>
.b2qzmwbhy {
  fill: var(--svg-color--fdc40c, #fdc40c);
  d: path("M0 27h64v8H0z");
}

.q8dsofbns {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M64 43c0 6.075-3.373 11-10 11H10C3.373 54 0 49.075 0 43V21c0-6.075 3.373-11 10-11h44c6.627 0 10 4.925 10 11z");
}

.rfevtxe1e {
  fill: var(--svg-color--fdc40c, #fdc40c);
  d: path("M20 10h9v44h-9z");
}

</style>
