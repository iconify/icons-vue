<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqq5nybqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-stick-left-rounded" /></template>
<style>
.cqq5nybqz {
  fill: currentColor;
  d: path("M17 15.35V18q0 .825-.587 1.413T15 20H9q-.825 0-1.412-.587T7 18v-2.65q-2.275-.8-3.637-2.187T2 10.075q0-2.525 2.913-4.3T12 4t7.088 1.775t2.912 4.3q0 1.7-1.362 3.088T17 15.35m-5.225-3.75V8q0-.2-.15-.35t-.35-.15t-.35.15t-.15.35v4q0 .2.15.35t.35.15h2.275q.2 0 .325-.125T14 12.05t-.125-.325t-.325-.125z");
}

</style>
