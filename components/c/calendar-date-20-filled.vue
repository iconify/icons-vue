<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mqotqd_bq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-date-20-filled" /></template>
<style>
.mqotqd_bq {
  fill: currentColor;
  d: path("M17 14.5a2.5 2.5 0 0 1-2.336 2.495L14.5 17h-9a2.5 2.5 0 0 1-2.495-2.336L3 14.5V7h14zM7.678 8.532a.5.5 0 0 0-.552.137h-.002l-.033.038l-.106.113c-.092.097-.223.231-.38.38c-.321.304-.725.648-1.105.867a.5.5 0 1 0 .5.866a6.6 6.6 0 0 0 1-.74V14a.5.5 0 0 0 1 0V9a.5.5 0 0 0-.322-.468m3.826-.282c-1.015 0-2 .702-2 1.75c0 .505.23.928.58 1.232c-.421.332-.701.816-.701 1.393c0 1.11 1.03 1.875 2.12 1.875s2.12-.766 2.12-1.875c0-.577-.28-1.06-.701-1.392A1.61 1.61 0 0 0 13.504 10c0-1.048-.985-1.75-2-1.75m-.001 3.5c.698 0 1.12.466 1.12.875c0 .41-.422.875-1.12.875s-1.12-.466-1.12-.875c0-.41.421-.875 1.12-.875m0-2.5c.642 0 1 .417 1 .75s-.358.75-1 .75c-.64 0-1-.417-1-.75s.36-.75 1-.75M14.5 3a2.5 2.5 0 0 1 2.495 2.336L17 5.5V6H3v-.5a2.5 2.5 0 0 1 2.336-2.495L5.5 3z");
}

</style>
