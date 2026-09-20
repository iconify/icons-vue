<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsrj7jwhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-3-day-24-filled" /></template>
<style>
.dsrj7jwhx {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zm-10 4a.75.75 0 0 0-.743.648L7 7.75v8.5l.007.102a.75.75 0 0 0 1.486 0l.007-.102v-8.5l-.007-.102A.75.75 0 0 0 7.75 7m8.5 0a.75.75 0 0 0-.743.648l-.007.102v8.5l.007.102a.75.75 0 0 0 1.486 0L17 16.25v-8.5l-.007-.102A.75.75 0 0 0 16.25 7M12 7a.75.75 0 0 0-.743.648l-.007.102v8.5l.007.102a.75.75 0 0 0 1.486 0l.007-.102v-8.5l-.007-.102A.75.75 0 0 0 12 7");
}

</style>
