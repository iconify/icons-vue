<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg3tkuwdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-outline-sharp" /></template>
<style>
.eg3tkuwdo {
  fill: currentColor;
  d: path("M17 23v-4H5V7H1V5h4V1h2v16h16v2h-4v4zm0-8V7H9V5h10v10z");
}

</style>
