<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="no5cnvb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:id-badge-sharp" /></template>
<style>
.no5cnvb1u {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 2L19 2L19 22L5 22ZM9 6L10 6L14 6L15 6M14 13C14 14.1046 13.1046 15 12 15C10.8954 15 10 14.1046 10 13C10 11.8954 10.8954 11 12 11C13.1046 11 14 11.8954 14 13ZM8 22C8 20.3431 9.3432 19 11 19L13 19C14.6569 19 16 20.3431 16 22");
}

</style>
