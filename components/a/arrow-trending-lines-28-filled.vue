<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ct5e31_uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-trending-lines-28-filled" /></template>
<style>
.ct5e31_uv {
  fill: currentColor;
  d: path("M5 20a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 1-1m6-5a1 1 0 0 1 1 1v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 1-1m6 2a1 1 0 0 1 1 1v6a1 1 0 0 1-2 0v-6a1 1 0 0 1 1-1m6-5a1 1 0 0 1 1 1v11a1 1 0 0 1-2 0V13a1 1 0 0 1 1-1m1-9a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0V6.414l-6.293 6.293a1 1 0 0 1-1.414 0L12 9.414l-6.293 6.293a1 1 0 1 1-1.414-1.414l7-7l.076-.068a1 1 0 0 1 1.338.068L16 10.586L21.586 5H19a1 1 0 1 1 0-2z");
}

</style>
