<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cuta3c28c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-arrow-counterclockwise-48-regular" /></template>
<style>
.cuta3c28c {
  fill: currentColor;
  d: path("M12.25 6A6.25 6.25 0 0 0 6 12.25v5.745L4.073 16.31a1.25 1.25 0 1 0-1.646 1.882l4 3.5a1.25 1.25 0 0 0 1.646 0l4-3.5a1.25 1.25 0 1 0-1.646-1.882L8.5 17.995V12.25a3.75 3.75 0 0 1 3.75-3.75h23.5a3.75 3.75 0 0 1 3.75 3.75V14h-28v.01a3.24 3.24 0 0 1 2.196 1.1c.361.413.6.891.717 1.39H39.5v19.25a3.75 3.75 0 0 1-3.75 3.75h-23.5a3.75 3.75 0 0 1-3.75-3.75v-8.5a1.25 1.25 0 1 0-2.5 0v8.5A6.25 6.25 0 0 0 12.25 42h23.5A6.25 6.25 0 0 0 42 35.75v-23.5A6.25 6.25 0 0 0 35.75 6zM18 23.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m6 2.5a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m11-2.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0M15.5 34a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m11-2.5a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0");
}

</style>
