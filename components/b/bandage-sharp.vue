<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgn3bhbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bandage-sharp" /></template>
<style>
.hgn3bhbyw {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.0294 3L21 7.9706L7.9706 21L3 16.0294L16.0294 3ZM12 7.0294L16.9706 12M7.0294 12L12 16.9706");
}

</style>
