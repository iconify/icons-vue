<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob5rnnpdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:delete-sharp" /></template>
<style>
.ob5rnnpdj {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2.0001 12L9 4L22 4L22 20L9 20L2.0001 12ZM10.7071 8.7071L17.2929 15.2929M17.2929 8.7071L10.7071 15.2929");
}

</style>
