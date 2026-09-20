<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ivy6a_b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-agenda-20-filled" /></template>
<style>
.ivy6a_b0a {
  fill: currentColor;
  d: path("M17 14.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3h9A2.5 2.5 0 0 1 17 5.5zm-3-8a.5.5 0 0 0-.41-.492L13.5 6h-7l-.09.008a.5.5 0 0 0 0 .984L6.5 7h7l.09-.008A.5.5 0 0 0 14 6.5m0 3.5a.5.5 0 0 0-.41-.492L13.5 9.5h-7l-.09.008a.5.5 0 0 0 0 .984l.09.008h7l.09-.008A.5.5 0 0 0 14 10m0 3.5a.5.5 0 0 0-.41-.492L13.5 13h-7l-.09.008a.5.5 0 0 0 0 .984L6.5 14h7l.09-.008A.5.5 0 0 0 14 13.5");
}

</style>
