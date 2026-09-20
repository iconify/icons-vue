<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfy-gbczr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:counter-24-filled" /></template>
<style>
.kfy-gbczr {
  fill: currentColor;
  d: path("M14.55 4q-.05.243-.05.5v3a2.5 2.5 0 0 0 5 0v-3q0-.24-.045-.467A3 3 0 0 1 22 7v10a3 3 0 0 1-2.846 2.996L19 20h-.5v-6.25a.75.75 0 0 0-1.355-.441l-.012.015l-.008.011l-.042.053a1.96 1.96 0 0 1-1.015.635a.75.75 0 0 0 .364 1.454q.309-.078.568-.199V20h-4.25V4zM7 9.5a1 1 0 0 1 1 1v3a1 1 0 1 1-2 0v-3a1 1 0 0 1 1-1M11.25 4v16H5l-.154-.004A3 3 0 0 1 2 17V7a3 3 0 0 1 3-3zM7 8a2.5 2.5 0 0 0-2.5 2.5v3a2.5 2.5 0 0 0 5 0v-3A2.5 2.5 0 0 0 7 8m10.865-4a1 1 0 0 1 .135.5v3a1 1 0 1 1-2 0v-3c0-.182.05-.353.135-.5z");
}

</style>
