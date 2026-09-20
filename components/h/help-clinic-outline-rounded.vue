<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bev-1u51r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:help-clinic-outline-rounded" /></template>
<style>
.bev-1u51r {
  fill: currentColor;
  d: path("M12.713 16.713Q13 16.425 13 16v-3q0-.425-.288-.712T12 12t-.712.288T11 13v3q0 .425.288.713T12 17t.713-.288m0-7Q13 9.425 13 9t-.288-.712T12 8t-.712.288T11 9t.288.713T12 10t.713-.288M6 21q-.825 0-1.412-.587T4 19v-9q0-.475.213-.9t.587-.7l6-4.5q.525-.4 1.2-.4t1.2.4l6 4.5q.375.275.588.7T20 10v9q0 .825-.588 1.413T18 21zm0-2h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
