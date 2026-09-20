<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blpsjgftn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cooking-sharp" /></template>
<style>
.blpsjgftn {
  fill: currentColor;
  d: path("M9 21v-3H2v-2h7q.825 0 1.413.588T11 18v3zm4 0v-3q0-.825.588-1.412T15 16h7v2h-7v3zm-7-6q-1.25 0-2.125-.875T3 12V8h18v4q0 1.25-.875 2.125T18 15zM3 7V5h6V4q0-.425.288-.712T10 3h4q.425 0 .713.288T15 4v1h6v2z");
}

</style>
