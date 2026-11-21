<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zf0alebkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:beehouse-sharp" /></template>
<style>
.zf0alebkq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1.3714 8.2514L2 8L12 4L22 8L22.6286 8.2514M12 4L12 2L12 1M3.8779 7.2673L4 8L6 20L18 20L20 8L20.1221 7.2673M9 10L10 10L14 10L15 10M12 20L12 22L12 23");
}

</style>
