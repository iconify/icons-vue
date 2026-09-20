<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j152v6d-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:area-chart-outline-rounded" /></template>
<style>
.j152v6d-t {
  fill: currentColor;
  d: path("M13.65 4.325L17 7h2q.825 0 1.413.588T21 9v11H3V9q0-.625.55-.9t1.05.1L7 10l3.775-5.275q.5-.7 1.35-.825t1.525.425M5 11v3.6L8 17l4-5.5l7 5.45V9h-2.7l-3.9-3.125l-4.95 6.95z");
}

</style>
