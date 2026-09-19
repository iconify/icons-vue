<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xyvq1nb5q"/><circle class="grxfpsbrv"/><path class="s3jsetlkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fansly" /></template>
<style>
.grxfpsbrv {
  cx: 24px;
  cy: 27.461px;
  r: 4.303px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.s3jsetlkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.695 26.67a.804.804 0 0 1-1.196-1.015a1.892 1.892 0 0 0-1.854 3.16a1.894 1.894 0 0 0 3.05-2.145M24 14.142l3.422-3.423a9.418 9.418 0 1 1 13.32 13.32l-.754.753M10.68 27.46l-3.42-3.42a9.418 9.418 0 1 1 13.319-13.32l.753.754");
}

.xyvq1nb5q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 14.141l13.319 13.32l-12.055 12.054a1.79 1.79 0 0 1-2.53 0L10.68 27.461z");
}

</style>
