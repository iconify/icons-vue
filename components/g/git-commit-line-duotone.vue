<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k90m4o-1e"/><path class="dd3evbk6v"/><path class="sduv6uq4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-commit-line-duotone" /></template>
<style>
.dd3evbk6v {
  d: path("M15 12.002L22 12.002");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k90m4o-1e {
  d: path("M2 11.9971L9 11.9971");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sduv6uq4w {
  d: path("M15 11.9971C15 13.6539 13.6569 14.9971 12 14.9971C10.3431 14.9971 9 13.6539 9 11.9971C9 10.3402 10.3431 8.99707 12 8.99707C13.6569 8.99707 15 10.3402 15 11.9971Z");
}

</style>
