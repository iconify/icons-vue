<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai2q2obhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:expand-more" /></template>
<style>
.ai2q2obhe {
  fill: currentColor;
  d: path("m12 15.375l-6-6l1.4-1.4l4.6 4.6l4.6-4.6l1.4 1.4z");
}

</style>
