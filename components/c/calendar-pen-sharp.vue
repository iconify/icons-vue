<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7avtbc9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:calendar-pen-sharp" /></template>
<style>
.e7avtbc9g {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.2199 21L3 21L3 5L21 5L21 9.3202M6 11L14 11M8 2L8 8M16 2L16 8M20.4142 15.6329L16.1715 19.8755L12.2189 20.9998L13.3431 17.0471L17.5858 12.8044C17.9609 12.4294 18.4696 12.2186 19 12.2186C20.1046 12.2186 21 13.1141 21 14.2186C21 14.7491 20.7893 15.2578 20.4142 15.6329Z");
}

</style>
