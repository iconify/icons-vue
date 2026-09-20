<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thha-lb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-add" /></template>
<style>
.thha-lb2s {
  fill: currentColor;
  d: path("M5 21V5q0-.825.588-1.412T7 3h7q-.5.75-.75 1.438T13 6q0 1.8 1.138 3.175T17 10.9q.575.075 1 .075t1-.075V21l-7-3zM17 9V7h-2V5h2V3h2v2h2v2h-2v2z");
}

</style>
