<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rfhwoeb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-chat-16-regular" /></template>
<style>
.rfhwoeb9u {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1-2.182 8.437l-1.789.544a.41.41 0 0 1-.51-.51l.544-1.79A4.5 4.5 0 0 1 11.5 7m0-5A2.5 2.5 0 0 1 14 4.5v2.1a5.5 5.5 0 0 0-1-.392V6H3v5.5A1.5 1.5 0 0 0 4.5 13h1.709q.113.4.282.773l-.07.227H4.5A2.5 2.5 0 0 1 2 11.5v-7A2.5 2.5 0 0 1 4.5 2zm-2 10a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm0-2a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zm-5-7A1.5 1.5 0 0 0 3 4.5V5h10v-.5A1.5 1.5 0 0 0 11.5 3z");
}

</style>
