<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mngmosbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-fill" /></template>
<style>
.mngmosbzn {
  fill: currentColor;
  d: path("m7.476 4.234l-.746-.747l4.384-2.165a2 2 0 0 1 .872-.207h.028c.303.003.6.073.872.207l8.004 3.953q.054.027.106.056L12.68 9.438ZM2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-2.468-2.468L13 22.621v-7.207l-2-2v9.207l-7.886-3.894A2 2 0 0 1 2 16.934V7.066l5.239 2.587l-5.946-5.946a.999.999 0 1 1 1.414-1.414m11.466 8.638L22 7.066v9.868a2.02 2.02 0 0 1-.499 1.324Z");
}

</style>
