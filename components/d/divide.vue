<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="r7ku0ubav"/><circle class="etycyt-mg"/><circle class="eccs3wb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:divide" /></template>
<style>
.eccs3wb1i {
  cx: 18px;
  cy: 29px;
  r: 4px;
  fill: var(--svg-color--31373d, #31373d);
}

.etycyt-mg {
  cx: 18px;
  cy: 7px;
  r: 4px;
  fill: var(--svg-color--31373d, #31373d);
}

.r7ku0ubav {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M34 18a3 3 0 0 1-3 3H5a3 3 0 1 1 0-6h26a3 3 0 0 1 3 3");
}

</style>
