<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="sf725nbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-date-28-filled" /></template>
<style>
.sf725nbec {
  fill: currentColor;
  d: path("M25 21.75A3.25 3.25 0 0 1 21.75 25H6.25A3.25 3.25 0 0 1 3 21.75V9.5h22zm-13.495-9.455a.75.75 0 0 0-.831.226l-.002.002l-.01.01a15 15 0 0 1-.74.8c-.462.464-1.031.97-1.547 1.268a.75.75 0 1 0 .75 1.298c.485-.28.964-.668 1.375-1.043v5.394a.75.75 0 0 0 1.5 0V13a.75.75 0 0 0-.495-.705M17 12c-1.422 0-2.75 1.028-2.75 2.5c0 .686.29 1.274.743 1.708c-.6.49-.993 1.204-.993 2.042c0 1.6 1.429 2.75 3 2.75s3-1.15 3-2.75c0-.838-.394-1.551-.994-2.042a2.34 2.34 0 0 0 .744-1.708c0-1.472-1.328-2.5-2.75-2.5m0 5c.914 0 1.5.64 1.5 1.25s-.586 1.25-1.5 1.25s-1.5-.64-1.5-1.25S16.086 17 17 17m0-3.5c.788 0 1.25.539 1.25 1s-.462 1-1.25 1s-1.25-.539-1.25-1s.462-1 1.25-1M21.75 3A3.25 3.25 0 0 1 25 6.25V8H3V6.25A3.25 3.25 0 0 1 6.25 3z");
}

</style>
