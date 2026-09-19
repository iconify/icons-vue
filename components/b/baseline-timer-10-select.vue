<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w379-7boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-timer-10-select" /></template>
<style>
.w379-7boc {
  fill: currentColor;
  d: path("M13 8v8h-3V8zm0-3h-3C8.34 5 7 6.34 7 8v8c0 1.66 1.34 3 3 3h3c1.66 0 3-1.34 3-3V8c0-1.66-1.34-3-3-3M1 8h2v11h3V5H1zm17.5 3c-.83 0-1.5.68-1.5 1.5v2c0 .82.67 1.5 1.5 1.5H21v1h-4v2h4.5c.83 0 1.5-.67 1.5-1.5v-2c0-.83-.67-1.5-1.5-1.5H19v-1h4v-2z");
}

</style>
