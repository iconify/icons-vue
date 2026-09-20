<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-h9ivb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:machine-image" /></template>
<style>
.j-h9ivb-s {
  fill: currentColor;
  d: path("M8 10V7h2v3Zm6 6v-3h2v3Zm-6 0v-3h5v3Zm3-6V7h5v3Zm-5 8h12V5H6Zm0 4q-.825 0-1.412-.587Q4 20.825 4 20V4q0-.825.588-1.413Q5.175 2 6 2h12q.825 0 1.413.587Q20 3.175 20 4v16q0 .825-.587 1.413Q18.825 22 18 22h-2l-1-1H9l-1 1Z");
}

</style>
