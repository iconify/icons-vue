<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynh0lkb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-fill-round" /></template>
<style>
.ynh0lkb0t {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-1.969-1.969A5.02 5.02 0 0 1 16 22H8a5 5 0 0 1-5-5V9a5 5 0 0 1 .839-2.775l.001-.001a5 5 0 0 1 .422-.548L1.293 2.707a.999.999 0 1 1 1.414-1.414M15 3a1 1 0 0 1 2 0v1.099A5.01 5.01 0 0 1 21 9v5a1 1 0 0 1-2 0v-4h-4.757l-6-6H15Zm-6.414 7H5v7a3.004 3.004 0 0 0 3 3h8c.693 0 1.369-.242 1.905-.681Z");
}

</style>
