<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lfu_eabgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lobster-sharp" /></template>
<style>
.lfu_eabgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 8.5h4.5l.804-.002L15 9.3l-.55 7.45h-4.9L9 9.3l-.054-.802zm-.45 3.75h5.4M9.45 14.5h5.1m-4.2 4.5h3.9l.33.5l.84 1.25l.33.5h-7.5l.33-.5l.84-1.25l.33-.5zm-.85-9l-2-1.5m7 1.5l2-1.5m-9.77-.54L3.77 6.29L3.25 6l.05-.6l.15-2.05l.05-.6l.43.42l1.04 1.01l.43.42l.28-.53l.29-.54l.28-.53l.33.5l1.34 2l.33.5l-.24.55l-.52 1.15l-.24.55zm10.54 0l2.96-1.67l.52-.29l-.05-.6l-.15-2.05l-.05-.6l-.43.42l-1.04 1.01l-.43.42l-.28-.53l-.29-.54l-.28-.53l-.33.5l-1.34 2l-.33.5l.24.55l.52 1.15l.24.55z");
}

</style>
