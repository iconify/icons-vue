<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhf7lc9ng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-2-sharp" /></template>
<style>
.qhf7lc9ng {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 2L15 2M3 7L21 7M6 7L18 7L18 22L6 22L6 7ZM10 10L10 19M14 10L14 19");
}

</style>
