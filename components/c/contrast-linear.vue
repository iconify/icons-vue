<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jp911_b0o"/><path class="m9ahr4bvj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:contrast-linear" /></template>
<style>
.jp911_b0o {
  d: path("M12 22C17.5228 22 22 17.523 22 12C22 6.477 17.5228 2 12 2M12 22C6.4772 22 2 17.523 2 12C2 6.477 6.4772 2 12 2M12 22V2");
}

.jx0p4fbya {
  fill: none;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m9ahr4bvj {
  stroke-linecap: round;
  d: path("M12 2L2 12M12 17L7.8883 21.112M12 12L4.9353 19.065M12 7L2.8883 16.112");
}

</style>
