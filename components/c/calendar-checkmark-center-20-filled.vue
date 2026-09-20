<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rcv_ccacd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-checkmark-center-20-filled" /></template>
<style>
.rcv_ccacd {
  fill: currentColor;
  d: path("M17 14.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5V7h14zm-3.646-5.354a.5.5 0 0 0-.707 0L9 12.793l-1.646-1.646l-.079-.065a.5.5 0 0 0-.629.771l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.707M14.5 3A2.5 2.5 0 0 1 17 5.5V6H3v-.5A2.5 2.5 0 0 1 5.5 3z");
}

</style>
