<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f62ffm-mu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chart-area-stacked-sharp" /></template>
<style>
.f62ffm-mu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18.8L10.7143 12.2L14.5714 15.5L21 10L21 21L3 21ZM2.6585 12.2988L3 12L10.7143 5.25L14.5714 8.625L21 3L21.2829 2.7525");
}

</style>
