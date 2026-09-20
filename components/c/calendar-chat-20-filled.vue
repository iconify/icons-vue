<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tgmwftbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-chat-20-filled" /></template>
<style>
.tgmwftbvq {
  fill: currentColor;
  d: path("M5.5 3A2.5 2.5 0 0 0 3 5.5V6h14v-.5A2.5 2.5 0 0 0 14.5 3zM17 7H3v7.5A2.5 2.5 0 0 0 5.5 17h3.922l.069-.227A5.5 5.5 0 0 1 17 9.6zm-7 7.5c0 .792.204 1.536.563 2.182l-.544 1.789a.409.409 0 0 0 .51.51l1.79-.544A4.5 4.5 0 1 0 10 14.5m2.5-1.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 1 1 0-1m-.5 2.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 0 1h-2a.5.5 0 0 1-.5-.5");
}

</style>
