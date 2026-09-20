<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2osambjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-right" /></template>
<style>
.t2osambjn {
  fill: currentColor;
  d: path("M10 17V7l5 5z");
}

</style>
