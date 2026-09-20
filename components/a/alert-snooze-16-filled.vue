<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x105hxb_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:alert-snooze-16-filled" /></template>
<style>
.x105hxb_u {
  fill: currentColor;
  d: path("M10.5 1.5A.5.5 0 0 1 11 1h3.5a.5.5 0 0 1 .41.787L11.96 6h2.54a.5.5 0 0 1 0 1H11a.5.5 0 0 1-.41-.787L13.54 2H11a.5.5 0 0 1-.5-.5M6 5.5a.5.5 0 0 1 .5-.5H9a.5.5 0 0 1 .384.82L7.568 8H9a.5.5 0 0 1 0 1H6.5a.5.5 0 0 1-.384-.82L7.932 6H6.5a.5.5 0 0 1-.5-.5m4.34-.673l.966-1.38A4.5 4.5 0 0 0 3.5 6.5v2.401l-.964 2.414A.5.5 0 0 0 3 12h10a.5.5 0 0 0 .464-.685L12.5 8.9V8H11c-.228 0-.448-.052-.646-.146A1.5 1.5 0 0 1 9 10H6.5a1.5 1.5 0 0 1-1.152-2.46l.553-.664A1.5 1.5 0 0 1 6.5 4H9a1.5 1.5 0 0 1 1.34.827M8 14.5A2 2 0 0 1 6.063 13h3.874A2 2 0 0 1 8 14.5");
}

</style>
