<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urahq4bqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-off-sharp" /></template>
<style>
.urahq4bqs {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 10L7.5 7.5M8.1732 3.9301L8.8974 3.2405C9.7047 2.4719 10.7972 2 12 2C14.4853 2 16.5 4.0147 16.5 6.5L16.5 10M10 10L4 10L4 22L20 22L20 20M20 15.3431L20 14.3431L20 10L15.6569 10L14.6569 10M1.7071 1.7071L22.2929 22.2929");
}

</style>
