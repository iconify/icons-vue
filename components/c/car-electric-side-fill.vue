<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwnos0bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-side-fill" /></template>
<style>
.hwnos0bmk {
  fill: currentColor;
  d: path("M6.293 7.293C7.008 6.578 7.961 6 9 6h3c1.039 0 1.992.578 2.707 1.293L18.414 11H19a3 3 0 0 1 3 3v2c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128H9.829a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16v-4c0-.265.105-.52.293-.707ZM11.414 11l.293-.293a.999.999 0 1 0-1.414-1.414l-2 2A1 1 0 0 0 9 13h1.586l-.293.293a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 13 11Zm-5.123 7.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
