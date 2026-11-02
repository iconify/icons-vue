<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sr2tw9bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-side-fill-sharp" /></template>
<style>
.sr2tw9bjy {
  fill: currentColor;
  d: path("M2 12c0-.265.105-.52.293-.707l5-5A1 1 0 0 1 8 6h5c.265 0 .52.105.707.293L18.414 11H21a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-1.171a3 3 0 0 1-5.658 0H9.829a3 3 0 0 1-5.658 0H3a1 1 0 0 1-1-1Zm9.414-1l.293-.293a.999.999 0 1 0-1.414-1.414l-2 2A1 1 0 0 0 9 13h1.586l-.293.293a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 13 11Zm-5.123 7.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
