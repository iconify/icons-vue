<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oye9ufsep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bookmark-x-sharp" /></template>
<style>
.oye9ufsep {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 11L20 22L12 18.4223L4 22L4 2L11 2M13.7071 1.7071L20.2929 8.2929M20.2929 1.7071L13.7071 8.2929");
}

</style>
