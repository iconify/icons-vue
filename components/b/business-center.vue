<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4vn8lbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:business-center" /></template>
<style>
.v4vn8lbbk {
  fill: currentColor;
  d: path("M4 21q-.825 0-1.412-.587T2 19v-4h7v2h6v-2h7v4q0 .825-.587 1.413T20 21zm7-6v-2h2v2zm-9-2V8q0-.825.588-1.412T4 6h4V4q0-.825.588-1.412T10 2h4q.825 0 1.413.588T16 4v2h4q.825 0 1.413.588T22 8v5h-7v-2H9v2zm8-7h4V4h-4z");
}

</style>
