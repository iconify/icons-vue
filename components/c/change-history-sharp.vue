<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otil38bqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:change-history-sharp" /></template>
<style>
.otil38bqp {
  fill: currentColor;
  d: path("M2 20L12 4l10 16z");
}

</style>
