<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y6qd5fb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-checkmark-16-regular" /></template>
<style>
.y6qd5fb9x {
  fill: currentColor;
  d: path("M6.208 3a5.5 5.5 0 0 0-.185 1H2.75a.75.75 0 0 0-.75.75V6h4.208q.149.524.394 1H2v4.25c0 .414.336.75.75.75h3.5a.75.75 0 0 0 .75-.75V7.66c.284.404.62.768 1 1.082v2.508A1.75 1.75 0 0 1 6.25 13h-3.5A1.75 1.75 0 0 1 1 11.25v-6.5C1 3.784 1.784 3 2.75 3zM15 12.5a.5.5 0 0 1-1 0V9.398a5.5 5.5 0 0 0 1-.656zM5.5 8a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1zm6-8a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m2.354 2.646a.5.5 0 0 0-.707 0L10.5 5.293l-.646-.647a.5.5 0 1 0-.708.708l1 1a.5.5 0 0 0 .707 0l3-3a.5.5 0 0 0 0-.708");
}

</style>
