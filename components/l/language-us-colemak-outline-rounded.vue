<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f60-69uaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:language-us-colemak-outline-rounded" /></template>
<style>
.f60-69uaj {
  fill: currentColor;
  d: path("M14.5 15H18V9h-3.5zM6 17q-.825 0-1.412-.587T4 15V9q0-.825.588-1.412T6 7h3.5q.425 0 .713.288T10.5 8t-.288.713T9.5 9H6v6h3.5q.425 0 .713.288T10.5 16t-.288.713T9.5 17zm8.5 0q-.825 0-1.412-.587T12.5 15V9q0-.825.588-1.412T14.5 7H18q.825 0 1.413.588T20 9v6q0 .825-.587 1.413T18 17z");
}

</style>
