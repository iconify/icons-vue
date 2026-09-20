<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb4a_s47q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:g-mobiledata-outline" /></template>
<style>
.zb4a_s47q {
  fill: currentColor;
  d: path("M9 17q-.825 0-1.412-.587T7 15V9q0-.825.588-1.412T9 7h5q.825 0 1.413.588T16 9H9v6h5v-2h-2v-2h4v4q0 .825-.587 1.413T14 17z");
}

</style>
