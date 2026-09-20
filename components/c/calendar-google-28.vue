<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vxln4tbcz"/><path class="uph4zqc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-google-28" /></template>
<style>
.uph4zqc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

.vxln4tbcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.4 22.5c0-1.667 1.334-3 2.89-3s3 1.333 3 3c0 .778-.334 1.556-.89 2.111c-1.222 1-5 3.889-5 3.889h5.89m5.06-4.5h-1.463a2.257 2.257 0 0 0-2.25 2.25a2.257 2.257 0 0 0 2.25 2.25h1.463a2.257 2.257 0 0 0 2.25-2.25A2.257 2.257 0 0 0 28.35 24m0 0a2.257 2.257 0 0 0 2.25-2.25a2.257 2.257 0 0 0-2.25-2.25h-1.463a2.257 2.257 0 0 0-2.25 2.25a2.257 2.257 0 0 0 2.25 2.25");
}

</style>
