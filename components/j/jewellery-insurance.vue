<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzu4jvhbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jewellery-insurance" /></template>
<style>
.mzu4jvhbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 15.25a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0M9.152 4.914l.411-.686a1.5 1.5 0 0 1 1.286-.728h2.302a1.5 1.5 0 0 1 1.286.728l.411.686a1.5 1.5 0 0 1-.31 1.91l-1.562 1.339a1.5 1.5 0 0 1-1.952 0L9.462 6.824a1.5 1.5 0 0 1-.31-1.91");
}

</style>
