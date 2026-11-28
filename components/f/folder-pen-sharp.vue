<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpk6bx9hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:folder-pen-sharp" /></template>
<style>
.dpk6bx9hg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.3842 20L3 20L3 4L9.5 4L12 6.5L21 6.5L21 8.5617M20.4142 14.6329L16.1715 18.8755L12.2189 19.9998L13.3431 16.0471L17.5858 11.8044C17.9609 11.4294 18.4696 11.2186 19 11.2186C20.1046 11.2186 21 12.1141 21 13.2186C21 13.7491 20.7893 14.2578 20.4142 14.6329Z");
}

</style>
