<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs52t000i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:battery-charging-fill-sharp" /></template>
<style>
.cs52t000i {
  fill: currentColor;
  d: path("M2 7a1 1 0 0 1 1-1h15a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm9.414 4l.293-.293a.999.999 0 1 0-1.414-1.414l-2 2A1 1 0 0 0 9 13h.586l-.293.293a.999.999 0 1 0 1.414 1.414l2-2A1 1 0 0 0 12 11ZM22 10v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0");
}

</style>
