<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0lkd8bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:business-messages-outline" /></template>
<style>
.j0lkd8bks {
  fill: currentColor;
  d: path("M7 20q-.825 0-1.412-.587T5 18V8.75L1 4h19q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zM5.3 6L7 8v10h13V6zm8.2 11.5l1.4-1.4l-1.1-1.1H18v-2H9zM9 11h9l-4.5-4.5l-1.4 1.4L13.2 9H9zm3.65 1");
}

</style>
