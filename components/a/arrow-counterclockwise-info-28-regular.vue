<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ec_-mj2fy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-counterclockwise-info-28-regular" /></template>
<style>
.ec_-mj2fy {
  fill: currentColor;
  d: path("M24.99 14.491a7.5 7.5 0 0 0-1.497-.87C23.293 8.55 19.12 4.5 14 4.5a9.47 9.47 0 0 0-6.928 3H9.75a.75.75 0 0 1 0 1.5h-4A.75.75 0 0 1 5 8.25v-4a.75.75 0 0 1 1.5 0v1.703A10.96 10.96 0 0 1 14 3c6.075 0 11 4.925 11 11q0 .248-.01.491M14 25q.248 0 .491-.01a7.5 7.5 0 0 1-.87-1.497C8.55 23.293 4.5 19.12 4.5 14q0-.59.07-1.16a.75.75 0 0 0-1.49-.18Q3 13.32 3 14c0 6.075 4.925 11 11 11m0-4.5a6.5 6.5 0 1 1 13 0a6.5 6.5 0 0 1-13 0m6.5 3.5a.5.5 0 0 0 .5-.5v-4a.5.5 0 0 0-1 0v4a.5.5 0 0 0 .5.5m0-7.125a.625.625 0 1 0 0 1.25a.625.625 0 0 0 0-1.25");
}

</style>
