<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw4bh0box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cooking-pot-off-sharp" /></template>
<style>
.jw4bh0box {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 11L4 21L20 21L20 20M1 11L11 11M3 7L7 7M20 15.3431L20 11M15.6569 11L23 11M11.6569 7L21 7M7.6569 3L16 3L16 7M1.7071 1.7071L22.2929 22.2929");
}

</style>
