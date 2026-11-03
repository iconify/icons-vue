<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbwhojosj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ev-charger-off" /></template>
<style>
.wbwhojosj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 14L14 22L2 22L2 5C2 4.1715 2.3358 3.4215 2.8787 2.8787M14 22L22 22M14 17L17 17M8.5714 8.5714L6 12L10 12L7 16M7.6569 2L11 2C12.6569 2 14 3.3431 14 5L14 8.3431M20 14.3431L20 10M18 6L22 6L22 8.5C22 9.3284 21.3284 10 20.5 10L19.5 10C18.6716 10 18 9.3284 18 8.5L18 6ZM22 6L22 4M18 6L18 4M2 2L22 22");
}

</style>
