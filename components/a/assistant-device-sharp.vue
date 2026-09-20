<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r07367bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assistant-device-sharp" /></template>
<style>
.r07367bao {
  fill: currentColor;
  d: path("M9.877 8.877Q9 9.754 9 11t.877 2.123T12 14t2.123-.877T15 11t-.877-2.123T12 8t-2.123.877M12 13q-.825 0-1.412-.587T10 11t.588-1.412T12 9t1.413.588T14 11t-.587 1.413T12 13m4.549 3.549q.22-.22.22-.549t-.22-.549t-.549-.22t-.549.22t-.22.549t.22.549t.549.22t.549-.22M5 20.231V7q0-1.671 1.165-2.835Q7.329 3 9 3h6q1.671 0 2.836 1.165Q19 5.329 19 7v13.23zm1-1h12V18H6z");
}

</style>
