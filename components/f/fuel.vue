<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4udzlbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fuel" /></template>
<style>
.p4udzlbqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21V5C3 3.9 3.8954 3 5 3H12C13.1046 3 14 3.9 14 5V21M3 21H14M3 21H2M14 21H15M15 11H16C17.1046 11 18 11.9 18 13V16C18 17.1 18.8954 18 20 18C21.1046 18 22 17.1 22 16V8.91C22 8.34 21.7306 7.8 21.2727 7.45L18 5M7 9H10");
}

</style>
