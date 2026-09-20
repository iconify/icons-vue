<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl1-ijbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-view-day-sharp" /></template>
<style>
.xl1-ijbaw {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V7h18v10zM3 5V3h18v2z");
}

</style>
