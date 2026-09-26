<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7gr7ac7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-plus-sharp" /></template>
<style>
.p7gr7ac7g {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.3859 5.0748L11 3.9963L2 11L2 22L20 22L20 11M8 22L8 15L14 15L14 22M19 1L19 9M15 5L23 5");
}

</style>
