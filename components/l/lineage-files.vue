<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ermpwpf6c"/><path class="o0m790rsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lineage-files" /></template>
<style>
.ermpwpf6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.878 13.042H27.846l-4.084-4.084H11.207l-4.085 4.084A2.62 2.62 0 0 0 4.5 15.664V36.42a2.62 2.62 0 0 0 2.622 2.622h33.756A2.62 2.62 0 0 0 43.5 36.42V15.664a2.62 2.62 0 0 0-2.622-2.622");
}

.o0m790rsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.24 26.04A19.265 19.265 0 0 0 8.665 37.732q0 .66.043 1.307");
}

</style>
