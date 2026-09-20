<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jn3rssbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-hook-down-left-32-filled" /></template>
<style>
.jn3rssbjv {
  fill: currentColor;
  d: path("M18.75 7a7.25 7.25 0 0 1 0 14.5h-8.482l2.866 2.866l.086.095a1.25 1.25 0 0 1-1.759 1.759l-.095-.086l-5-5a1.25 1.25 0 0 1 0-1.768l5-5a1.25 1.25 0 0 1 1.768 1.768L10.268 19h8.482a4.75 4.75 0 0 0 0-9.5H10A1.25 1.25 0 0 1 10 7z");
}

</style>
