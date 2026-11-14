<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umilhs0yk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:abc" /></template>
<style>
.umilhs0yk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 16.5l2.25-9l2.25 9m-3.5-3.25H6M9.75 12h2a2.25 2.25 0 0 0 0-4.5h-2v9H12a2.25 2.25 0 0 0 0-4.5m9.5-3.5c-.75-.75-1.75-1-2.5-1c-1.25 0-2.25 2-2.25 4.5s1 4.5 2.25 4.5c.75 0 1.75-.25 2.5-1");
}

</style>
