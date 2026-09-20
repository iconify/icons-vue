<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="z7t4s009y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-undo-28-filled" /></template>
<style>
.z7t4s009y {
  fill: currentColor;
  d: path("M13.251 5.501a5.125 5.125 0 0 1 7.248 7.248L8.955 24.293a1 1 0 0 0 1.414 1.414l11.544-11.544A7.125 7.125 0 1 0 11.837 4.087l-4.5 4.499V3a1 1 0 1 0-2 0v8a1 1 0 0 0 1 1h8.003a1 1 0 1 0 0-2H8.752z");
}

</style>
