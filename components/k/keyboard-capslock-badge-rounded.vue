<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-bewuq9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-capslock-badge-rounded" /></template>
<style>
.a-bewuq9d {
  fill: currentColor;
  d: path("M8 17h8q.425 0 .713-.288T17 16t-.288-.712T16 15H8q-.425 0-.712.288T7 16t.288.713T8 17m4-7.6l2.9 2.9q.275.275.7.275t.7-.275t.275-.7t-.275-.7l-3.6-3.6Q12.4 7 12 7t-.7.3l-3.6 3.6q-.275.275-.275.7t.275.7t.7.275t.7-.275zM5 21q-.825 0-1.412-.587T3 19V5q0-.825.588-1.412T5 3h14q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21z");
}

</style>
