<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ralqle4ob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:champagne-pop" /></template>
<style>
.ralqle4ob {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 6.804za1.25 1.25 0 0 1 .458 1.707l-.785 1.359a1.75 1.75 0 0 0-.193 1.254l.587 2.644a1.75 1.75 0 0 1-.193 1.255l-2.535 4.39a1.75 1.75 0 0 1-2.39.64l-3.898-2.25a1.75 1.75 0 0 1-.64-2.39l2.535-4.39a1.75 1.75 0 0 1 .989-.795l2.583-.813a1.75 1.75 0 0 0 .99-.795l.784-1.359A1.25 1.25 0 0 1 15 6.804m2.875-4.137za1.25 1.25 0 0 1 .458 1.708a1.25 1.25 0 0 1-1.708.458a1.25 1.25 0 0 1-.458-1.708a1.25 1.25 0 0 1 1.708-.458M12.5 3.5h.01M20.5 7h.01");
}

</style>
