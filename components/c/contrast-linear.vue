<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jp911_b0o"/><path class="ww7a06bvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:contrast-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jp911_b0o {
  d: path("M12 22C17.5228 22 22 17.523 22 12C22 6.477 17.5228 2 12 2M12 22C6.4772 22 2 17.523 2 12C2 6.477 6.4772 2 12 2M12 22V2");
}

.ww7a06bvx {
  d: path("M12 2L2 12M12 17L7.8883 21.112M12 12L4.9353 19.065M12 7L2.8883 16.112");
}

</style>
