<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6wm93bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dresser-rounded" /></template>
<style>
.s6wm93bzu {
  fill: currentColor;
  d: path("M4 21V5q0-.825.588-1.412T6 3h12q.825 0 1.413.588T20 5v16h-2v-2H6v2zm2-10h5V5H6zm7-4h5V5h-5zm0 4h5V9h-5zm-3 5h4v-2h-4z");
}

</style>
