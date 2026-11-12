<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="hrxlgg64z"/><path class="er9_2_bjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-dot-bold-duotone" /></template>
<style>
.er9_2_bjd {
  fill: currentColor;
  d: path("M12 11.25C12.4142 11.25 12.75 11.5858 12.75 12C12.75 12.4142 12.4142 12.75 12 12.75C11.5858 12.75 11.25 12.4142 11.25 12C11.25 11.5858 11.5858 11.25 12 11.25Z");
}

.hrxlgg64z {
  cx: 12px;
  cy: 12px;
  r: 10px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
