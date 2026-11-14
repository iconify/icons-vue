<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hcp1k1bnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:jo-staff" /></template>
<style>
.hcp1k1bnu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.303 6.697L6.697 17.303M18.364 2.808l2.828 2.828l-2.474 2.475l-2.829-2.829ZM5.282 15.889l2.829 2.829l-2.475 2.474l-2.828-2.828Z");
}

</style>
