<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikbz9v8be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:floor-lamp-outline-rounded" /></template>
<style>
.ikbz9v8be {
  fill: currentColor;
  d: path("M11.288 18.713Q11 18.425 11 18v-7H6q-.5 0-.8-.4t-.15-.9L7 3.4q.2-.625.725-1.013T8.9 2h6.2q.65 0 1.175.388T17 3.4l1.95 6.3q.15.5-.15.9t-.8.4h-5v7q0 .425-.288.713T12 19t-.712-.288M7.35 9h9.3L15.1 4H8.9zM9 22q-.425 0-.712-.288T8 21t.288-.712T9 20h6q.425 0 .713.288T16 21t-.288.713T15 22zm3-15.5");
}

</style>
