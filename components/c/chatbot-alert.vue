<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnl22i_pv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chatbot-alert" /></template>
<style>
.cnl22i_pv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 17H4V5.5h15v6.4m-7.5-9.4v3m-3 5.5h.01m5.99 0h.01M18 14.75v3.5M18 21h.01");
}

</style>
