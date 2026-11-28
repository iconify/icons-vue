<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0o12bb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bin-x-sharp" /></template>
<style>
.z0o12bb2z {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 2L15 2M3 7L21 7M6 7L18 7L18 22L6 22ZM9.7071 12.7071L14.2929 17.2929M14.2929 12.7071L9.7071 17.2929");
}

</style>
