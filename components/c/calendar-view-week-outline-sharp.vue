<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y80307bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-view-week-outline-sharp" /></template>
<style>
.y80307bbw {
  fill: currentColor;
  d: path("M12.5 18h3.25V6H12.5zm-4.25 0h3.25V6H8.25zM4 18h3.25V6H4zm12.75 0H20V6h-3.25zM3 19V5h18v14z");
}

</style>
