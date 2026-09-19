<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ndl21p7gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitbuy" /></template>
<style>
.ndl21p7gu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.464 17.036C11.464 10.112 17.076 4.5 24 4.5s12.536 5.612 12.536 12.536s-5.613 12.536-12.534 12.536a5.571 5.571 0 0 1 0-11.143a12.535 12.535 0 1 1-12.537 12.536z");
}

</style>
