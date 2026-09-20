<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvi7gmhgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-dashes-24-filled" /></template>
<style>
.jvi7gmhgb {
  fill: currentColor;
  d: path("M11 3a1 1 0 1 0 0 2h6.586l-2.293 2.293a1 1 0 0 0 1.414 1.414L19 6.414V13a1 1 0 1 0 2 0V4a1 1 0 0 0-1-1zm2.707 8.707a1 1 0 0 0-1.414-1.414l-3 3a1 1 0 1 0 1.414 1.414zm-6 6a1 1 0 1 0-1.414-1.414l-3 3a1 1 0 1 0 1.414 1.414z");
}

</style>
