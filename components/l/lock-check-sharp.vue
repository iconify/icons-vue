<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgosup8-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lock-check-sharp" /></template>
<style>
.vgosup8-e {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 10L7.5 6.5C7.5 4.0147 9.5147 2 12 2C14.4853 2 16.5 4.0147 16.5 6.5L16.5 10M4 10L4 22L20 22L20 10L4 10ZM8.7071 15.7071L11 18L15.2929 13.7071");
}

</style>
