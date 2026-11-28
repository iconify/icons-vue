<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kl5e4hbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-lines-sharp" /></template>
<style>
.kl5e4hbzu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4L9.5 4L12 6.5L21 6.5L21 20L3 20L3 4ZM7 11L17 11M7 15L14 15");
}

</style>
