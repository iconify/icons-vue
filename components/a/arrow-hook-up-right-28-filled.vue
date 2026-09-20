<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="a1e8l1b8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-up-right-28-filled" /></template>
<style>
.a1e8l1b8n {
  fill: currentColor;
  d: path("M6.782 19.977C7.99 21.222 9.758 22 12 22h7a1 1 0 1 0 0-2h-7c-1.758 0-2.99-.597-3.782-1.415C7.414 17.755 7 16.637 7 15.5s.414-2.256 1.218-3.085C9.01 11.597 10.242 11 12 11h7.586l-3.293 3.293a1 1 0 1 0 1.414 1.414l5-5a1 1 0 0 0 0-1.414l-5-5a1 1 0 1 0-1.414 1.414L19.586 9H12c-2.242 0-4.01.778-5.218 2.023C5.586 12.256 5 13.887 5 15.5s.586 3.244 1.782 4.477");
}

</style>
