<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r7dgjpwoc"/><path class="ihxun8b5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gate-io" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ihxun8b5f {
  fill: var(--svg-color--17e6a1, #17e6a1);
  d: path("M16.95 7.05H12V12h4.95z");
}

.r7dgjpwoc {
  fill: var(--svg-color--2354e6, #2354e6);
  d: path("M12 16.95a4.95 4.95 0 1 1 0-9.9V3a9 9 0 1 0 9 9h-4.05A4.95 4.95 0 0 1 12 16.95");
}

</style>
