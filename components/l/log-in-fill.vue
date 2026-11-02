<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bik34-9wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-in-fill" /></template>
<style>
.bik34-9wf {
  fill: currentColor;
  d: path("M7 7V5a3 3 0 0 1 3-3h7a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3v-2a1 1 0 0 1 2 0v2a1 1 0 0 0 1 1h7a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-7a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0m4.293 2.707a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414L12.586 13H5a1 1 0 0 1 0-2h7.586Z");
}

</style>
