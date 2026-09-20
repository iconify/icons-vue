<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="tn3tc4fsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-import-28-regular" /></template>
<style>
.tn3tc4fsy {
  fill: currentColor;
  d: path("M25.251 5a.75.75 0 0 1 .75.75v16a.75.75 0 0 1-1.5 0v-16a.75.75 0 0 1 .75-.75M14.22 6.72a.75.75 0 0 1 1.06 0l6.5 6.5a.75.75 0 0 1 0 1.06l-6.5 6.5a.75.75 0 1 1-1.06-1.06l5.22-5.22H2.753a.75.75 0 0 1 0-1.5h16.685l-5.22-5.22a.75.75 0 0 1 0-1.06");
}

</style>
