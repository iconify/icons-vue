<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jxfqgrbol"/><path class="w3k5beb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:acdisplay" /></template>
<style>
.jxfqgrbol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.86 4.5a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h27.2a2 2 0 0 0 2-2V30.83h-2.92v7.79H8.79V9.38h25.35v1.95h2.92V6.5a2 2 0 0 0-2-2Z");
}

.w3k5beb3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.31 14.25a6.82 6.82 0 0 0-6.82 6.83v6.82h6.82a6.83 6.83 0 1 0 0-13.65");
}

</style>
