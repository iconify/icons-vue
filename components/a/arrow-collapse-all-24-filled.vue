<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl9mjtb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-collapse-all-24-filled" /></template>
<style>
.wl9mjtb1g {
  fill: currentColor;
  d: path("M2 5a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m4.293 3.293a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1-1.414 1.414L8 11.414V19a1 1 0 1 1-2 0v-7.586l-1.293 1.293a1 1 0 0 1-1.414-1.414zM21 10h-9a1 1 0 1 1 0-2h9a1 1 0 1 1 0 2");
}

</style>
