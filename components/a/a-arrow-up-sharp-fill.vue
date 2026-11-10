<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc1488bny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:a-arrow-up-sharp-fill" /></template>
<style>
.hc1488bny {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.93 18.6273L7.002 6L12.074 18.6273M4.19 13H9.813M19.002 19V8M22.295 11.2929L19.002 8L15.709 11.2929");
}

</style>
