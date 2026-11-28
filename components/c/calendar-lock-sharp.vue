<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq2kilxeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-lock-sharp" /></template>
<style>
.yq2kilxeg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 21L3 21L3 5L21 5L21 9.6706M6 11L12.9181 11M8 2L8 8M16 2L16 8M14 16L21 16L21 21L14 21ZM15.5 16L15.5 14C15.5 12.8954 16.3954 12 17.5 12C18.6046 12 19.5 12.8954 19.5 14L19.5 16");
}

</style>
