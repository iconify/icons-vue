<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjzndgbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-box-outline-sharp" /></template>
<style>
.hjzndgbmd {
  fill: currentColor;
  d: path("M11 17h2v-4h4v-2h-4V7h-2v4H7v2h4zm-8 4V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
