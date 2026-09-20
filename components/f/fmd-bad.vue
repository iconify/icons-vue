<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvx48nbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fmd-bad" /></template>
<style>
.kvx48nbxt {
  fill: currentColor;
  d: path("M11.5 12.173h1V6.481h-1zm.5 2.962q.262 0 .439-.177q.176-.177.176-.439t-.177-.438t-.438-.177t-.438.177t-.177.438t.177.439t.438.177m0 5.884q-3.525-3.117-5.31-5.814q-1.786-2.697-1.786-4.909q0-3.173 2.066-5.234Q9.037 3 12 3t5.03 2.062q2.066 2.061 2.066 5.234q0 2.212-1.785 4.909q-1.786 2.697-5.311 5.814");
}

</style>
