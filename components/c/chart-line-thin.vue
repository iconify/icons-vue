<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lq-c-8b_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-line-thin" /></template>
<style>
.lq-c-8b_a {
  fill: currentColor;
  d: path("M228 208a4 4 0 0 1-4 4H32a4 4 0 0 1-4-4V48a4 4 0 0 1 8 0v103.19L93.37 101a4 4 0 0 1 5-.19l61.41 46.05L221.37 93a4 4 0 0 1 5.26 6l-64 56a4 4 0 0 1-5 .19l-61.41-46L36 161.81V204h188a4 4 0 0 1 4 4");
}

</style>
