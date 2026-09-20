<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o55ok5b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:find-in-page-sharp" /></template>
<style>
.o55ok5b8b {
  fill: currentColor;
  d: path("M5 21V3h9.539L19 8.346v10.996l-4.55-4.611q.275-.387.413-.8T15 13q0-1.246-.877-2.123T12 10t-2.123.877T9 13t.877 2.123T12 16q.479 0 .892-.128t.839-.422l5.177 5.146V21zm5.588-6.587Q10 13.825 10 13t.588-1.412T12 11t1.413.588T14 13t-.587 1.413T12 15t-1.412-.587");
}

</style>
