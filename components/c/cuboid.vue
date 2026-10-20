<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmek22erh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cuboid" /></template>
<style>
.mmek22erh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 8L7.7071 3.2929C7.8946 3.1054 8.149 3 8.4142 3L21 3L21 15.5858C21 15.851 20.8946 16.1054 20.7071 16.2929L16 21L4 21C3.4477 21 3 20.5523 3 20L3 8ZM3 8L16 8L16 21M16 8L21 3");
}

</style>
