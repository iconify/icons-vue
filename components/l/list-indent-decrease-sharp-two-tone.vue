<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxdm9_bgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:list-indent-decrease-sharp-two-tone" /></template>
<style>
.xxdm9_bgc {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12L2 12M5.2929 8.7071L2 12L5.2929 15.2929M11 6L23 6M11 12L23 12M11 18L23 18");
}

</style>
