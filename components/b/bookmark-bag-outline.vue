<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eph7xun9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-bag-outline" /></template>
<style>
.eph7xun9w {
  fill: currentColor;
  d: path("M11.288 14.788q.212-.213.212-.538V14h1v.25q0 .325.213.538t.537.212t.538-.213t.212-.537V14q.425 0 .713-.288T15 13V9q0-.425-.288-.712T14 8h-.5V7q0-.425-.288-.712T12.5 6h-1q-.425 0-.712.288T10.5 7v1H10q-.425 0-.712.288T9 9v4q0 .425.288.713T10 14v.25q0 .325.213.538t.537.212t.538-.213M11.5 8V7h1v1zM5 21V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v16l-7-3zm2-3.05l5-2.15l5 2.15V5H7zM7 5h10z");
}

</style>
