<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bue_65boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-zap-sharp" /></template>
<style>
.bue_65boa {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.3859 5.0748L12 3.9963L3 11L3 22L21 22L21 11M9 22L9 15L15 15L15 22M20.2929 1.7071L17 5L21 5L17.7071 8.2929");
}

</style>
