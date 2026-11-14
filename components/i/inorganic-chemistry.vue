<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmxqlnbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inorganic-chemistry" /></template>
<style>
.vmxqlnbti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 20.5v-13L12 4l2.5 3.5v13m-9.5 0v-8L7.25 10l2.25 2m5 2l2.25-2.5L19 14v6.5m-16 0h18");
}

</style>
