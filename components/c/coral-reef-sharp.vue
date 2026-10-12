<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdr71thay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coral-reef-sharp" /></template>
<style>
.zdr71thay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25C3.25 18.75 5 17.5 7 17.5h1.375l1.125.75l1.2-2H13c2.25 0 3.75 1.25 4.5 2.5c2-.25 3.5.75 3.75 2.5ZM7 17.5V10m0 3H4.25V8.5M7 12.25h2.5V7.5m3 8.75V8.5m0 2.75H15V8.5m1-3c1.25-1.5 3-1.5 4 0c-1 1.5-2.75 1.5-4 0Zm0 0l-1.25-1.25M16 5.5l-1.25 1.25");
}

</style>
