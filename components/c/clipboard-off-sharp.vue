<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iss2zcmcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clipboard-off-sharp" /></template>
<style>
.iss2zcmcq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4L4 22L20 22L20 20M20 15.3431L20 14.3431L20 4L17 4M6.6569 2L7.6569 2L17 2L17 7L12.6569 7L11.6569 7M1.7071 1.7071L22.2929 22.2929");
}

</style>
