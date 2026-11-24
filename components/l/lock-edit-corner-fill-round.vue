<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="km--nqm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-edit-corner-fill-round" /></template>
<style>
.km--nqm2k {
  fill: currentColor;
  d: path("M7 8.099V7a5 5 0 0 1 10 0v1.098a5 5 0 0 1 1.5.572a4.9 4.9 0 0 1 1.83 1.83a.997.997 0 0 1-.366 1.366a1 1 0 0 1-.5.134H14a3 3 0 0 0-3 3v6a1 1 0 0 1-1 1H8a5 5 0 0 1-5-5v-4a5.01 5.01 0 0 1 4-4.901M15 7a3 3 0 1 0-6 0v1h6Zm-2 14v-3c0-.265.105-.52.293-.707l4-4a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 17 22h-3a1 1 0 0 1-1-1");
}

</style>
