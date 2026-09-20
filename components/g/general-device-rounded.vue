<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay1xvbcfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:general-device-rounded" /></template>
<style>
.ay1xvbcfq {
  fill: currentColor;
  d: path("M9 18q-.425 0-.712-.288T8 17V5q0-.825.588-1.412T10 3h4q.825 0 1.413.588T16 5v12q0 .425-.288.713T15 18zm0 1h6q.425 0 .713.288T16 20t-.288.713T15 21H9q-.425 0-.712-.288T8 20t.288-.712T9 19");
}

</style>
