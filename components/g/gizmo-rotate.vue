<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h95-gybqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gizmo-rotate" /></template>
<style>
.h95-gybqu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.851 7.851q-1.539.284-2.844.8Q1.75 9.936 1.75 12t3.257 3.349q1.305.516 2.844.8q.284 1.539.8 2.844Q9.936 22.25 12 22.25t3.349-3.257q.516-1.305.8-2.844q1.539-.284 2.844-.8Q22.25 14.064 22.25 12t-3.257-3.349q-1.305-.516-2.844-.8q-.284-1.539-.8-2.844Q14.064 1.75 12 1.75T8.651 5.007q-.516 1.305-.8 2.844");
}

</style>
