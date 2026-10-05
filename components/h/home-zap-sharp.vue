<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7ruc3brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-zap-sharp" /></template>
<style>
.u7ruc3brr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.3859 5.0748L11 3.9963L2 11L2 22L20 22L20 11M8 22L8 15L14 15L14 22M19.2929 1.7071L16 5L20 5L16.7071 8.2929");
}

</style>
