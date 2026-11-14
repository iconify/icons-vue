<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9a-4iqdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:explosives-magazine" /></template>
<style>
.a9a-4iqdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.375 8h.25a2.625 2.625 0 0 1 2.625 2.625v8.25A2.625 2.625 0 0 1 6.625 21.5h-.25a2.625 2.625 0 0 1-2.625-2.625v-8.25A2.625 2.625 0 0 1 6.375 8m5.5-2.5h.25a2.625 2.625 0 0 1 2.625 2.625v10.75a2.625 2.625 0 0 1-2.625 2.625h-.25a2.625 2.625 0 0 1-2.625-2.625V8.125A2.625 2.625 0 0 1 11.875 5.5m5.5 2.5h.25a2.625 2.625 0 0 1 2.625 2.625v8.25a2.625 2.625 0 0 1-2.625 2.625h-.25a2.625 2.625 0 0 1-2.625-2.625v-8.25A2.625 2.625 0 0 1 17.375 8M3.75 15h16.5M12 5.5c0-1.75 1.5-1.5 2.25-3");
}

</style>
