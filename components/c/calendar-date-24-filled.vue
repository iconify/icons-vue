<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n78kxobrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-date-24-filled" /></template>
<style>
.n78kxobrp {
  fill: currentColor;
  d: path("M21 17.75A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V8.5h18zM9.996 10.541a.75.75 0 0 0-.834.243l-.004.005l-.02.024l-.09.105a8 8 0 0 1-1.7 1.448a.75.75 0 0 0 .802 1.268a9 9 0 0 0 .85-.61V17a.75.75 0 0 0 1.5 0v-5.75a.75.75 0 0 0-.504-.709m4.504-.291c-1.18 0-2.25.891-2.25 2.125c0 .512.186.963.485 1.317A2.3 2.3 0 0 0 12 15.375c0 1.363 1.173 2.375 2.5 2.375s2.5-1.012 2.5-2.375a2.3 2.3 0 0 0-.736-1.683c.3-.354.486-.805.486-1.317c0-1.234-1.07-2.125-2.25-2.125m0 4.25c.606 0 1 .443 1 .875s-.394.875-1 .875s-1-.443-1-.875s.394-.875 1-.875m0-2.75c.477 0 .75.34.75.625s-.273.625-.75.625s-.75-.34-.75-.625s.273-.625.75-.625M17.75 3A3.25 3.25 0 0 1 21 6.25V7H3v-.75A3.25 3.25 0 0 1 6.25 3z");
}

</style>
