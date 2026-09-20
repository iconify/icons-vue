<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or0wenvbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-add-on-outline" /></template>
<style>
.or0wenvbz {
  fill: currentColor;
  d: path("M17 22v-3h-3v-2h3v-3h2v3h3v2h-3v3zM5 20q-.825 0-1.412-.587T3 18V6q0-.825.588-1.412T5 4h1V2h2v2h6V2h2v2h1q.825 0 1.413.588T19 6v6.1q-.5-.075-1-.075t-1 .075V10H5v8h7q0 .5.075 1t.275 1zM5 8h12V6H5zm0 0V6z");
}

</style>
