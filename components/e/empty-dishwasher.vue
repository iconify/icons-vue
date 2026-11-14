<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aod7bd3_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:empty-dishwasher" /></template>
<style>
.aod7bd3_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.027 17H5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211q-.058-.108-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T2.5 14.5V8H19v4.1M6.5 8V4m4.25 4V4M15 8V4m3 17v-6m-2.5 2.5L18 15l2.5 2.5");
}

</style>
