<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ojl39zbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-outdoor" /></template>
<style>
.ojl39zbuc {
  fill: currentColor;
  d: path("M5 20V9.5l7-5.27l7 5.27V11h-6.461q-.825 0-1.413.588T10.539 13v4q0 .825.587 1.413t1.413.587H19v1zm7.539-2.384q-.262 0-.439-.177T11.923 17v-4q0-.261.177-.438t.439-.177h4q.261 0 .438.177t.177.438v1.462L19 13.489v3.022l-1.846-.972V17q0 .262-.177.439t-.438.177z");
}

</style>
