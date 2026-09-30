<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj6ber3fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:copy-check-sharp" /></template>
<style>
.pj6ber3fr {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 5L16.0001 2L2 2L2 16.0001L5 16M8 8L22 8L22 22L8 22L8 8ZM11.7071 14.7071L14 17L18.2929 12.7071");
}

</style>
