<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8ypm9bik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-right-left-sharp" /></template>
<style>
.w8ypm9bik {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 6L21 6M17.7071 2.7071L21 6L17.7071 9.2929M22 18L3 18M6.2929 14.7071L3 18L6.2929 21.2929");
}

</style>
