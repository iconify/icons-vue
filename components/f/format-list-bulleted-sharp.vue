<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opt88vb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-list-bulleted-sharp" /></template>
<style>
.opt88vb7m {
  fill: currentColor;
  d: path("M9 19v-2h12v2zm0-6v-2h12v2zm0-6V5h12v2zM5 20q-.825 0-1.412-.587T3 18t.588-1.412T5 16t1.413.588T7 18t-.587 1.413T5 20m0-6q-.825 0-1.412-.587T3 12t.588-1.412T5 10t1.413.588T7 12t-.587 1.413T5 14M3.588 7.413Q3 6.825 3 6t.588-1.412T5 4t1.413.588T7 6t-.587 1.413T5 8t-1.412-.587");
}

</style>
