<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6id4bchy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-us-colemak-outline" /></template>
<style>
.d6id4bchy {
  fill: currentColor;
  d: path("M14.5 15H18V9h-3.5zM6 17q-.825 0-1.412-.587T4 15V9q0-.825.588-1.412T6 7h4.5v2H6v6h4.5v2zm8.5 0q-.825 0-1.412-.587T12.5 15V9q0-.825.588-1.412T14.5 7H18q.825 0 1.413.588T20 9v6q0 .825-.587 1.413T18 17z");
}

</style>
