<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgv6vubxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flask-conical-sharp" /></template>
<style>
.lgv6vubxn {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 2L14.5 2L14.5 8L19.9999 22L4.0001 22L9.5 8L9.5 2ZM7 2L17 2M5.5715 18L18.4285 18");
}

</style>
