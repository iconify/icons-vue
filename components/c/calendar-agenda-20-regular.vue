<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ce9gb4aev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-20-regular" /></template>
<style>
.ce9gb4aev {
  fill: currentColor;
  d: path("M17 14.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3h9A2.5 2.5 0 0 1 17 5.5zm-1 0v-9A1.5 1.5 0 0 0 14.5 4h-9A1.5 1.5 0 0 0 4 5.5v9A1.5 1.5 0 0 0 5.5 16h9a1.5 1.5 0 0 0 1.5-1.5m-2-8a.5.5 0 0 1-.41.492L13.5 7h-7a.5.5 0 0 1-.09-.992L6.5 6h7a.5.5 0 0 1 .5.5m0 3.5a.5.5 0 0 1-.41.492l-.09.008h-7a.5.5 0 0 1-.09-.992L6.5 9.5h7a.5.5 0 0 1 .5.5m0 3.5a.5.5 0 0 1-.41.492L13.5 14h-7a.5.5 0 0 1-.09-.992L6.5 13h7a.5.5 0 0 1 .5.5");
}

</style>
