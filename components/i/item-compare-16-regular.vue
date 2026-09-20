<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="px4t25b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:item-compare-16-regular" /></template>
<style>
.px4t25b6n {
  fill: currentColor;
  d: path("M8 2a.5.5 0 0 1 .5.5v11a.5.5 0 0 1-1 0v-11A.5.5 0 0 1 8 2M4.5 5.5A1.5 1.5 0 0 1 6 7v2a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 1 9V7a1.5 1.5 0 0 1 1.5-1.5zm9 0A1.5 1.5 0 0 1 15 7v2a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 10 9V7a1.5 1.5 0 0 1 1.5-1.5zm-11 1A.5.5 0 0 0 2 7v2a.5.5 0 0 0 .5.5h2A.5.5 0 0 0 5 9V7a.5.5 0 0 0-.5-.5zm9 0a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5h2A.5.5 0 0 0 14 9V7a.5.5 0 0 0-.5-.5z");
}

</style>
