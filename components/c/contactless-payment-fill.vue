<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f7zy82b4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:contactless-payment-fill" /></template>
<style>
.f7zy82b4x {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24M97.07 155.74a8 8 0 1 1-14.14-7.48a42.79 42.79 0 0 0 0-40.52a8 8 0 0 1 14.14-7.48a59.33 59.33 0 0 1 0 55.48m28 16a8 8 0 1 1-14.12-7.52a77.07 77.07 0 0 0 0-72.48a8 8 0 1 1 14.12-7.52a93 93 0 0 1-.01 87.54Zm28 16a8 8 0 0 1-14.07-7.51a110.62 110.62 0 0 0 0-104.46a8 8 0 0 1 14.12-7.54a126.67 126.67 0 0 1-.05 119.54Z");
}

</style>
