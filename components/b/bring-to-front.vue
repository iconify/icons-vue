<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ace5b7bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bring-to-front" /></template>
<style>
.ace5b7bic {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 12.5H4.75q-2.25 0-2.25-2.25v-5.5q0-.932.659-1.591T4.75 2.5h5.5q2.25 0 2.25 2.25V7h2.25Q17 7 17 9.25v2.25h1.125q3.375 0 3.375 3.375v3.25q0 3.375-3.375 3.375h-3.25q-3.375 0-3.375-3.375V17H9.25Q7 17 7 14.75zM7 11H4.75Q4 11 4 10.25v-5.5Q4 4 4.75 4h5.5q.75 0 .75.75V7H9.25Q7 7 7 9.25zm1.5.75v3q0 .75.75.75h2.25v-.625q0-3.375 3.375-3.375h.625V9.25q0-.75-.75-.75h-5.5q-.75 0-.75.75z");
}

</style>
