<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4_7g3b8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comment-outline" /></template>
<style>
.h4_7g3b8y {
  fill: currentColor;
  d: path("M6 14h12v-2H6zm0-3h12V9H6zm0-3h12V6H6zm16 14l-4-4H4q-.825 0-1.412-.587T2 16V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4zM4 16h14.85L20 17.125V4H4zm0 0V4z");
}

</style>
