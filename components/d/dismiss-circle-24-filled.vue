<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz3m_uydl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dismiss-circle-24-filled" /></template>
<style>
.dz3m_uydl {
  fill: currentColor;
  d: path("M12 2c5.523 0 10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12S6.477 2 12 2m3.53 6.47l-.084-.073a.75.75 0 0 0-.882-.007l-.094.08L12 10.939l-2.47-2.47l-.084-.072a.75.75 0 0 0-.882-.007l-.094.08l-.073.084a.75.75 0 0 0-.007.882l.08.094L10.939 12l-2.47 2.47l-.072.084a.75.75 0 0 0-.007.882l.08.094l.084.073a.75.75 0 0 0 .882.007l.094-.08L12 13.061l2.47 2.47l.084.072a.75.75 0 0 0 .882.007l.094-.08l.073-.084a.75.75 0 0 0 .007-.882l-.08-.094L13.061 12l2.47-2.47l.072-.084a.75.75 0 0 0 .007-.882zl-.084-.073z");
}

</style>
