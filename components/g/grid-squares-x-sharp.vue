<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf6zq1beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-x-sharp" /></template>
<style>
.bf6zq1beg {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 14L10 14L10 21L3 21L3 14ZM3 3L10 3L10 10L3 10L3 3ZM14 3L21 3L21 10L14 10L14 3ZM14.7071 14.7071L20.2929 20.2929M20.2929 14.7071L14.7071 20.2929");
}

</style>
