<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="xllcxm7wq"/><path class="jm8csxnlh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ferret" /></template>
<style>
.jm8csxnlh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 11.5h.01");
}

.xllcxm7wq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5c0-.5.3-.9.75-1.1l3-1.4c.75-.5 1.75-.75 2.75-.75h7.5c2 0 3.5 1.4 3.5 3.25c0 1.25-.75 2.25-1.75 2.75v2.25h-2.25v-2.25H10.5v2.25H8.25V15c-.75-.25-1.5-.75-2-1.25L3.5 13.6c-.45-.1-.75-.6-.75-1.1M20 14c.75 1.25 1.25 3 1.25 5M7.75 9.6L7.5 7.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
