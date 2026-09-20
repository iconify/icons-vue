<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="idtv9e7ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-20-filled" /></template>
<style>
.idtv9e7ms {
  fill: currentColor;
  d: path("M5 13h11.5a.5.5 0 0 0 .416-.777L14.101 8l2.815-4.223A.5.5 0 0 0 16.5 3h-12a.5.5 0 0 0-.5.5v14a.5.5 0 0 0 1 0z");
}

</style>
