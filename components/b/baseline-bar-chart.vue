<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afos8yb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-bar-chart" /></template>
<style>
.afos8yb_y {
  fill: currentColor;
  d: path("M4 9h4v11H4zm12 4h4v7h-4zm-6-9h4v16h-4z");
}

</style>
