<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0jlzec7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4g-mobiledata-outline" /></template>
<style>
.b0jlzec7q {
  fill: currentColor;
  d: path("M7 17v-3H3V7h2v5h2V7h2v5h2v2H9v3zm14-6v4q0 .825-.587 1.413T19 17h-5q-.825 0-1.412-.587T12 15V9q0-.825.588-1.412T14 7h5q.825 0 1.413.588T21 9h-7v6h5v-2h-2.5v-2z");
}

</style>
