<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q2n_kcv7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cron" /></template>
<style>
.q2n_kcv7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 37h5m-5 3h5m4.5-1.5a7 7 0 1 1-14 0a7 7 0 0 1 14 0M23.397 14.664V25.45l9.93 5.734m.117 12.131A21.5 21.5 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24a21.5 21.5 0 0 1-2.177 9.428");
}

</style>
