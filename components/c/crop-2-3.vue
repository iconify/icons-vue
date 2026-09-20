<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_mmmkb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-2-3" /></template>
<style>
.w_mmmkb1s {
  fill: currentColor;
  d: path("M8 22q-.825 0-1.412-.587T6 20V4q0-.825.588-1.412T8 2h8q.825 0 1.413.588T18 4v16q0 .825-.587 1.413T16 22z");
}

</style>
