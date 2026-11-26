<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1rg3vo2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-arrow-up-sharp" /></template>
<style>
.k1rg3vo2s {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4.001L11.998 6.75L7 9.499L2.002 6.75ZM1.4472 12.0326L7 14.809L12.5528 12.0326M1.4472 17.2826L7 20.059L12.5528 17.2826M15 3L23 3M19 22L19 7M15.7071 10.2929L19 7L22.2929 10.2929");
}

</style>
