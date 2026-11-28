<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljzxtlbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-signature-sharp" /></template>
<style>
.ljzxtlbcj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 2L4 2L4 22L20 22L20 8L14 2ZM14 2L14 8L20 8M7.2147 13.8955L8 13.7228C10.1818 13.2431 10.4242 11.324 10.6666 12.2835C10.9091 13.2431 11.3939 14.2026 12.1212 13.9627C12.8485 13.7228 13.0909 12.5234 13.5757 13.2431C14.0606 13.9627 15.2728 13.9627 16 13.9627L17 13.9627M7 18L17 18");
}

</style>
