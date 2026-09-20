<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kkrwq_bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-health-outline-sharp" /></template>
<style>
.kkrwq_bsl {
  fill: currentColor;
  d: path("M11 16.5h2V14h2.5v-2H13V9.5h-2V12H8.5v2H11zM5 20V9.5l7-5.27l7 5.27V20zm1-1h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
