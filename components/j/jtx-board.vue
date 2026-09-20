<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c2unztb4u"/><path class="cd8y20bdw"/><circle class="o7eoo8ufw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jtx-board" /></template>
<style>
.c2unztb4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-1.116 13.995l-7.799 10.334m7.799 0l-7.799-10.334");
}

.cd8y20bdw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.97 16.05v11.7c0 1.17.78 1.95 1.95 1.95h.585m-4.484-10.334h4.094m-7.869-.296v11.7a3.91 3.91 0 0 1-3.9 3.899c-.975 0-1.95-.39-2.73-1.17");
}

.o7eoo8ufw {
  cx: 17.245px;
  cy: 14.391px;
  r: 0.75px;
  fill: currentColor;
}

</style>
