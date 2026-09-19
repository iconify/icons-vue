<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kj7bn4bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-add-chart" /></template>
<style>
.kj7bn4bta {
  fill: currentColor;
  d: path("M6 9.99h2v7H6zm8 3h2v4h-2zm-4-6h2v10h-2zM20 7V4h-2v3h-3v2h3v3h2V9h3V7zm-2 12H4V5h12V3H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2v-5h-2z");
}

</style>
