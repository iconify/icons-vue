<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqi-cgy2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:film-canister-sharp" /></template>
<style>
.uqi-cgy2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 5.25h10v15h-10zm3-2.5h4v2.5h-4zm8 5.5h5v5.25l-.71.71l-1.33 1.33l-.71.71h-3.25v-8zm-11 1.5h10m-10 6h10");
}

</style>
