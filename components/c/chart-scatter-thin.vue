<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fskh1d_wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-scatter-thin" /></template>
<style>
.fskh1d_wt {
  fill: currentColor;
  d: path("M228 208a4 4 0 0 1-4 4H32a4 4 0 0 1-4-4V48a4 4 0 0 1 8 0v156h188a4 4 0 0 1 4 4m-96-52a8 8 0 1 0-8-8a8 8 0 0 0 8 8m-24-56a8 8 0 1 0-8-8a8 8 0 0 0 8 8m-32 72a8 8 0 1 0-8-8a8 8 0 0 0 8 8m96-48a8 8 0 1 0-8-8a8 8 0 0 0 8 8m24-40a8 8 0 1 0-8-8a8 8 0 0 0 8 8m-8 88a8 8 0 1 0-8-8a8 8 0 0 0 8 8");
}

</style>
