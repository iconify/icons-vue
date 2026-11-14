<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5rwqnmvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chatbot-knowledge" /></template>
<style>
.q5rwqnmvz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.2 17H2.5V6.5H17v6.7M9 2.5h3v3H9Zm1.5 3v1M7 11.75h.01m5.49 0h.01M14 16.5c1.5-.75 3-.75 4 .25c1-1 2.5-1 4-.25v5c-1.5-.75-3-.75-4 .25c-1-1-2.5-1-4-.25Zm4 .25v5");
}

</style>
