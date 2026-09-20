<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="xm0c1ubgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-work-week-28-regular" /></template>
<style>
.xm0c1ubgx {
  fill: currentColor;
  d: path("M6.25 25A3.25 3.25 0 0 1 3 21.75V6.25A3.25 3.25 0 0 1 6.25 3h15.5A3.25 3.25 0 0 1 25 6.25v15.5A3.25 3.25 0 0 1 21.75 25zm0-1.5h15.5a1.75 1.75 0 0 0 1.75-1.75V6.25a1.75 1.75 0 0 0-1.75-1.75H6.25A1.75 1.75 0 0 0 4.5 6.25v15.5c0 .966.784 1.75 1.75 1.75M7.5 8.75A.75.75 0 0 1 8.25 8h11.5a.75.75 0 0 1 .75.75v5.5a.75.75 0 0 1-.75.75H8.25a.75.75 0 0 1-.75-.75zM9 9.5v4h10v-4z");
}

</style>
