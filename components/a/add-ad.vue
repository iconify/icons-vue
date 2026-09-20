<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6u4nufaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-ad" /></template>
<style>
.s6u4nufaq {
  fill: currentColor;
  d: path("M18 20v-3h-3v-2h3v-3h2v3h3v2h-3v3zM3 21q-.825 0-1.412-.587T1 19V5q0-.825.588-1.412T3 3h14q.825 0 1.413.588T19 5v5h-2V8H3v11h13v2z");
}

</style>
