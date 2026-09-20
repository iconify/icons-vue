<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7igpe7uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-chart-sharp" /></template>
<style>
.v7igpe7uu {
  fill: currentColor;
  d: path("M7.23 16.5h1v-6h-1zm3.77 0h1v-9h-1zm3.77 0h1v-3h-1zM17.5 8V6h-2V5h2V3h1v2h2v1h-2v2zm-14 12V4h10.923v5.077H19.5V20z");
}

</style>
