<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj2mrnbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fertile-outline-rounded" /></template>
<style>
.hj2mrnbaw {
  fill: currentColor;
  d: path("M13.325 3.5q.725.85 1.375 1.725t1.25 1.8L20.4 3.7q.225-.175.5-.2t.55.1t.413.375T22 4.5V12q0 2.075-.787 3.9t-2.138 3.175t-3.175 2.138T12 22t-3.9-.788t-3.175-2.137T2.788 15.9T2 12V4.5q0-.275.138-.525T2.55 3.6t.55-.1t.5.2l4.425 3.325q.6-.925 1.263-1.8T10.675 3.5q.25-.3.6-.462T12 2.875t.725.163t.6.462m4.35 14.175Q20 15.35 20 12V6.5l-4.6 3.45q-1.125-1.8-1.825-2.85T12 5q-.875 1.075-1.625 2.175T8.6 9.95L4 6.5V12q0 3.35 2.325 5.675T12 20t5.675-2.325M12 12.5");
}

</style>
