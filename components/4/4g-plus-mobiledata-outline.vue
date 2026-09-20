<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-oqh_byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4g-plus-mobiledata-outline" /></template>
<style>
.a-oqh_byo {
  fill: currentColor;
  d: path("M20 15v-2h-2v-2h2V9h2v2h2v2h-2v2zM5 17v-3H1V7h2v5h2V7h2v5h1v2H7v3zm12-6v4q0 .825-.587 1.413T15 17h-4q-.825 0-1.412-.587T9 15V9q0-.825.588-1.412T11 7h4q.825 0 1.413.588T17 9h-6v6h4v-2h-2v-2z");
}

</style>
