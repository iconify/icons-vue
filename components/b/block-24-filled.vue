<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yai0f0baj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:block-24-filled" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.yai0f0baj {
  d: path("M12 2.001c5.524 0 10 4.477 10 10s-4.476 10-10 10c-5.522 0-10-4.477-10-10s4.478-10 10-10zm4.25 9.25h-8.5a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5z");
  fill: currentColor;
}

</style>
