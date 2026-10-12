<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b31qs6a4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:caret-left-right" /></template>
<style>
.b31qs6a4o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.18 11.24l5.14-4.23q.93-.76.93.44v9.1q0 1.2-.93.44l-5.14-4.23q-.93-.76 0-1.52m15.64 0l-5.14-4.23q-.93-.76-.93.44v9.1q0 1.2.93.44l5.14-4.23q.93-.76 0-1.52");
}

</style>
