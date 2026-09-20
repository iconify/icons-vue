<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ekk6opb4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-20-filled" /></template>
<style>
.ekk6opb4d {
  fill: currentColor;
  d: path("M3 10a7 7 0 0 1 14 0v1h-3.5a.5.5 0 0 0-.5.5v6a.5.5 0 0 0 .5.5H16a2 2 0 0 0 2-2v-6a8 8 0 1 0-16 0v6a2 2 0 0 0 2 2h2.5a.5.5 0 0 0 .5-.5v-6a.5.5 0 0 0-.5-.5H3z");
}

</style>
