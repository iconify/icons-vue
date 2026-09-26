<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmcxdubgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-left-duotone" /></template>
<style>
.xmcxdubgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19H14C16.7614 19 19 16.7614 19 14C19 11.2386 16.7614 9 14 9H6M10 5L5.18766 8.60957C4.93745 8.80973 4.93745 9.19027 5.18766 9.39043L10 13");
}

</style>
