<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="els9svunr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-format-textdirection-r-to-l" /></template>
<style>
.els9svunr {
  fill: currentColor;
  d: path("M10 10v5h2V4h2v11h2V4h2V2h-8C7.79 2 6 3.79 6 6s1.79 4 4 4m-2 7v-3l-4 4l4 4v-3h12v-2z");
}

</style>
