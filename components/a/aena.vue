<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nonc5bqkg"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aena" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nonc5bqkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.501 24.57c3.277 0 7.421.65 12.304 2.203c5.628 1.787 11.494 4.807 16.699 9.518c-3.577-4.6-5.923-9.457-7.5-14.057c-1.612-4.695-2.576-9.471-2.221-14.501c.004-.05.05-.097 0-.108v-.13c-.048-.014.018.011 0 .057c-1.707 3.875-4.752 7.32-8.188 10.185c-3.168 2.638-6.745 5.3-11.094 6.834Z");
}

</style>
