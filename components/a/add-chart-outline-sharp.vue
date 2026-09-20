<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w278-ijzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-chart-outline-sharp" /></template>
<style>
.w278-ijzw {
  fill: currentColor;
  d: path("M7.23 16.5h1v-6h-1zm3.77 0h1v-9h-1zm3.77 0h1v-3h-1zM3.5 20V4h10.923v1H4.5v14h14V9.077h1V20zm14-12V6h-2V5h2V3h1v2h2v1h-2v2zm-6 4");
}

</style>
