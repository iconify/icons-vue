<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fok1zjbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ar-on-you-outline-sharp" /></template>
<style>
.fok1zjbaq {
  fill: currentColor;
  d: path("M16.964 7.034Q19 9.067 19 11.997t-2.033 4.967T12.003 19t-4.966-2.033T5 12.003t2.034-4.966T11.997 5t4.967 2.034m-.714 9.216Q18 14.5 18 12t-1.75-4.25T12 6T7.75 7.75T6 12t1.75 4.25T12 18t4.25-1.75m-2.311-1.707q.872-.572 1.292-1.543H8.769q.42.971 1.292 1.543q.873.573 1.939.573t1.939-.573m-4.936-3.965q.233.23.577.23t.575-.233t.23-.578t-.233-.575q-.234-.23-.578-.23t-.575.234t-.23.577t.234.575m4.846 0q.233.23.578.23t.574-.233t.23-.578t-.233-.575t-.578-.23t-.575.234t-.23.577t.234.575M2 6V2h4v1H3v3zm0 16v-4h1v3h3v1zm16-.192v-1h3v-3h1v4zM21 6V3h-3V2h4v4zm-9 6");
}

</style>
