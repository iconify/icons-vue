<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmbstzmjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:adb" /></template>
<style>
.zmbstzmjn {
  fill: currentColor;
  d: path("M5 11v-1q0-1.8.813-3.287T8 4.275L6.125 2.4L7 1.5l2.125 2.125q.65-.3 1.388-.462T12 3t1.488.163t1.387.462L17 1.5l.875.9L16 4.275q1.375.95 2.188 2.438T19 10v1zm10.713-2.287Q16 8.425 16 8t-.288-.712T15 7t-.712.288T14 8t.288.713T15 9t.713-.288m-6 0Q10 8.426 10 8t-.288-.712T9 7t-.712.288T8 8t.288.713T9 9t.713-.288m-2.675 12.25Q5 18.926 5 16v-4h14v4q0 2.925-2.037 4.963T12 23t-4.962-2.037");
}

</style>
