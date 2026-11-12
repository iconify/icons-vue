<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1_d_sxhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-conveyor-sharp" /></template>
<style>
.b1_d_sxhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7h12v6H6ZM3 17h18v4H3ZM9 7V3h6v4m-5 0v6m4-6v6");
}

</style>
