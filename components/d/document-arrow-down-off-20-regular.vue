<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wd1pgbb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-arrow-down-off-20-regular" /></template>
<style>
.wd1pgbb-z {
  fill: currentColor;
  d: path("M5.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-1.244-1.243A2 2 0 0 1 14 18H9.743q.382-.462.657-1H14a1 1 0 0 0 1-1v-.293l-10-10v3.315a5.5 5.5 0 0 0-1 .185v-4.5L2.146 2.854a.5.5 0 0 1 0-.708M5.5 12a.5.5 0 0 0-.5.5v2.793l-1.146-1.146a.5.5 0 1 0-.708.707l2.002 2.002a.5.5 0 0 0 .705-.002l2-2a.5.5 0 1 0-.707-.707L6 15.293V12.5a.5.5 0 0 0-.5-.5m5.086-10a1.5 1.5 0 0 1 1.06.44l3.914 3.914a1.5 1.5 0 0 1 .44 1.06v6.465l-1-1V8h-3.5A1.5 1.5 0 0 1 10 6.5V3H6a1 1 0 0 0-.644.235l-.708-.708C5.004 2.2 5.478 2 6 2zM11 6.5a.5.5 0 0 0 .5.5h3.293L11 3.207z");
}

</style>
