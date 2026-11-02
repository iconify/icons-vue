<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mla7qacyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flip-horizontal" /></template>
<style>
.mla7qacyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V8c0-.369.631-.369 1 0l3 3a1.414 1.414 0 0 1 0 2l-3 3c-.369.369-1 .369-1 0zm9-7v2m0 4v2m0 4v2m9-7V8c0-.369-.631-.369-1 0l-3 3a1.414 1.414 0 0 0 0 2l3 3c.369.369 1 .369 1 0z");
}

</style>
