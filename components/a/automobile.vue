<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="iu65b5bdv"/><path class="l2389qguv"/><circle class="tieb_sdfa"/><circle class="mcsilq5el"/><circle class="rh0m0lm3b"/><circle class="fec_atbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:automobile" /></template>
<style>
.fec_atbaj {
  cx: 27px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.iu65b5bdv {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M13 32h20s3 0 3-4c0-2 0-6-1-7s-8-7-11-7h-6c-3 0-10 7-10 7l-4 1s-3 1-3 3v3s-1 .338-1 1.957C0 32 2 32 2 32z");
}

.l2389qguv {
  fill: var(--svg-color--bbddf5, #bbddf5);
  d: path("M20 16h-2c-2 0-8 6-8 6s4.997-.263 10-.519zm10 3c-1-1-5-3-7-3h-1v5.379c4.011-.204 7.582-.379 8-.379c1 0 1-1 0-2");
}

.mcsilq5el {
  cx: 10px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.rh0m0lm3b {
  cx: 27px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.tieb_sdfa {
  cx: 10px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

</style>
