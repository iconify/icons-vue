<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="izmd_8wfh"/><circle class="gp5-k0b3n"/><path class="m5r182b2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:field-hockey" /></template>
<style>
.gp5-k0b3n {
  cx: 26.5px;
  cy: 29.5px;
  r: 6.5px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.izmd_8wfh {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M4 21c2.409 0 2 2 2 3s0 3 2 3s3.464-2.465 7-6L36 0v7S22.5 21.5 18 26s-7 7-10 7c-3.513 0-7-2.605-7-7c0-4 2-5 3-5");
}

.m5r182b2m {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M25.01 18.712C30.254 13.171 36 7 36 7V0L25.01 10.99zM22 21.878l1-1.049V13l-1 1z");
}

</style>
