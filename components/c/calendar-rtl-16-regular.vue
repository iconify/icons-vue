<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xgm0ckbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-rtl-16-regular" /></template>
<style>
.xgm0ckbki {
  fill: currentColor;
  d: path("M10.752 8.997a.748.748 0 1 1 0-1.497a.748.748 0 0 1 0 1.497m-.749 1.752a.748.748 0 1 0 1.497 0a.748.748 0 0 0-1.497 0M8 8.997A.748.748 0 1 1 8 7.5a.748.748 0 0 1 0 1.497m-.749 1.752a.748.748 0 1 0 1.497 0a.748.748 0 0 0-1.497 0m-2-1.752a.748.748 0 1 1 0-1.497a.748.748 0 0 1 0 1.497M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM13 6H3v5.5A1.5 1.5 0 0 0 4.5 13h7a1.5 1.5 0 0 0 1.5-1.5zm-1.5-3h-7A1.5 1.5 0 0 0 3 4.5V5h10v-.5A1.5 1.5 0 0 0 11.5 3");
}

</style>
