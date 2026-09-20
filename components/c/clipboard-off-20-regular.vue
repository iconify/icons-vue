<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="med9-ibvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clipboard-off-20-regular" /></template>
<style>
.med9-ibvu {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .707 0l15 15a.5.5 0 0 1-.707.707l-1.16-1.16A1.5 1.5 0 0 1 14.5 18h-9A1.5 1.5 0 0 1 4 16.5V4.707L2.146 2.854a.5.5 0 0 1 0-.708M5 16.5a.5.5 0 0 0 .5.5h9a.5.5 0 0 0 .5-.5v-.793l-10-10zM11.5 2a1.5 1.5 0 0 1 1.415 1H14.5A1.5 1.5 0 0 1 16 4.5v9.379l-1-1V4.5a.5.5 0 0 0-.5-.5h-1.585A1.5 1.5 0 0 1 11.5 5h-3a1.5 1.5 0 0 1-1.415-1H6.12l-.96-.96Q5.323 3 5.5 3h1.585A1.5 1.5 0 0 1 8.5 2zm-3 1a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

</style>
