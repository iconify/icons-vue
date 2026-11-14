<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk_8a36hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flash-fill" /></template>
<style>
.kk_8a36hv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.172 13.915L14.5 10.5H9.25l1.25-8l-7.5 10h6l-2 9l3.707-5.437m5.043 1.687a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-2V13.5m0 6.25V22m-2-4.25H13.5m6.25 0H22m-5.75-1.5L15 15m4.25 1.25L20.5 15m-4.25 4.25L15 20.5m4.25-1.25l1.25 1.25");
}

</style>
