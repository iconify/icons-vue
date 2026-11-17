<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_b-bgbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dishwasher-fill-sharp" /></template>
<style>
.t_b-bgbvp {
  fill: currentColor;
  d: path("M3 8V3a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v5Zm5.01-3H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M11 5a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-8 5h18v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm13 2H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2");
}

</style>
