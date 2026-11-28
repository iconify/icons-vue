<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_lzs29mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-closed-sharp" /></template>
<style>
.u_lzs29mq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.8 7.7333L2 8C4.3607 11.1476 8.0655 13 12 13C15.9345 13 19.6393 11.1476 22 8L22.2 7.7333M19.3473 10.6127L21.3142 13.3199L21.6137 13.7321M14.5989 12.7268L15.2946 15.9999L15.4346 16.6588M9.4011 12.7268L8.7054 16L8.5654 16.6588M4.6527 10.6127L2.6858 13.3199L2.3863 13.7321");
}

</style>
