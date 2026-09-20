<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eki9zbc3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-48-regular" /></template>
<style>
.eki9zbc3p {
  fill: currentColor;
  d: path("M35.5 24.165a.84.84 0 0 1 1 0q1.133.84 2.277 1.455q1.38.74 2.779 1.152q1.787.529 3.611.528c.46 0 .833.37.833.825V33.9c0 5.501-3.286 9.543-9.694 12.042a.84.84 0 0 1-.612 0C32.79 44.81 30.525 43.36 28.92 41.6a11.1 11.1 0 0 1-1.86-2.75Q26.002 36.614 26 33.9v-5.775a.83.83 0 0 1 .833-.825c2.96 0 5.843-1.038 8.667-3.135M24 4a9 9 0 0 1 9 9v5.006a6.25 6.25 0 0 1 5.941 5.4a18 18 0 0 1-1.249-.846a2.84 2.84 0 0 0-1.934-.55a3.74 3.74 0 0 0-3.008-1.51h-17.5a3.75 3.75 0 0 0-3.75 3.75v13.5a3.75 3.75 0 0 0 3.75 3.75h11.048q.516.76 1.144 1.448q.501.547 1.065 1.052H15.25A6.25 6.25 0 0 1 9 37.75v-13.5a6.25 6.25 0 0 1 6-6.244V13a9 9 0 0 1 9-9m0 29.5a2.5 2.5 0 0 1 0-5zm0-27a6.5 6.5 0 0 0-6.5 6.5v5h13v-5A6.5 6.5 0 0 0 24 6.5");
}

</style>
