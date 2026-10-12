<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss9fwxb_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bow-tie-sharp" /></template>
<style>
.ss9fwxb_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.07 7.22l2.86 1.56l1.32.72v5l-1.32.72l-2.86 1.56l-1.32.72v-11zm15.86 0l-2.86 1.56l-1.32.72v5l1.32.72l2.86 1.56l1.32.72v-11zm-9.18 2.03h2.5v5.5h-2.5zm-5.25 1v3.5m13-3.5v3.5");
}

</style>
