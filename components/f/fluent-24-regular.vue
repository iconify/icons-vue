<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn6cotrml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:fluent-24-regular" /></template>
<style>
.hn6cotrml {
  fill: currentColor;
  d: path("M11.915 2.082a.75.75 0 0 1 .67 0l6 3a.75.75 0 0 1 0 1.341l-4.658 2.33l4.658 2.329a.75.75 0 0 1 0 1.341L13 15.216v6.034a.75.75 0 0 1-1.149.635l-6-3.77a.75.75 0 0 1-.351-.634V5.752a.75.75 0 0 1 .415-.671zM7 6.216v10.85l4.5 2.827v-5.14a.75.75 0 0 1 .415-.671l4.658-2.33l-4.658-2.329a.75.75 0 0 1 0-1.341l4.658-2.33l-4.323-2.16z");
}

</style>
