<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d5kw8bb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-12-filled" /></template>
<style>
.d5kw8bb3j {
  fill: currentColor;
  d: path("M1.5 5.2a2.7 2.7 0 0 1 2.7-2.7h.05a.75.75 0 0 1 0 1.5H4.2A1.2 1.2 0 0 0 3 5.2v.6A1.2 1.2 0 0 0 4.2 7h.05a.75.75 0 0 1 0 1.5H4.2a2.7 2.7 0 0 1-2.7-2.7zm9 0a2.7 2.7 0 0 0-2.7-2.7h-.05a.75.75 0 0 0 0 1.5h.05A1.2 1.2 0 0 1 9 5.2v.6A1.2 1.2 0 0 1 7.8 7h-.05a.75.75 0 0 0 0 1.5h.05a2.7 2.7 0 0 0 2.7-2.7zm-5.75-.45a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5z");
}

</style>
