<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mw6ihrbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-rounded" /></template>
<style>
.mw6ihrbum {
  fill: currentColor;
  d: path("m12 18l-4.2 1.8q-1 .425-1.9-.162T5 17.975V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v12.975q0 1.075-.9 1.663t-1.9.162z");
}

</style>
