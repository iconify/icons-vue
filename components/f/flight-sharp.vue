<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v33ql1b9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flight-sharp" /></template>
<style>
.v33ql1b9k {
  fill: currentColor;
  d: path("M7 22v-2.5l3-2.1v-3.6L2 17v-3l8-5.6V4q0-.825.588-1.412T12 2t1.413.588T14 4v4.4l8 5.6v3l-8-3.2v3.6l3 2.1V22l-5-1.5z");
}

</style>
