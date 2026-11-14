<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezfqoj2xi"/><path class="w6td0rqjw"/><path class="tujfzqnjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:battery-charge-cycle" /></template>
<style>
.ezfqoj2xi {
  d: path("M5.072 8A8 8 0 0 1 20 12");
}

.tujfzqnjl {
  d: path("M2 14.5L4 12l2.5 2.5M8 10h6.5v4H8Zm8.5 1.25v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w6td0rqjw {
  d: path("M17.5 9.5L20 12l2-2.5M18.928 16A8 8 0 0 1 4 12");
}

</style>
