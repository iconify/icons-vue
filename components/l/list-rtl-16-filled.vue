<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ue1lgqb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:list-rtl-16-filled" /></template>
<style>
.ue1lgqb1c {
  fill: currentColor;
  d: path("M5 3.75A.75.75 0 0 1 5.75 3h7.5a.75.75 0 0 1 0 1.5h-7.5A.75.75 0 0 1 5 3.75m1 8a.75.75 0 0 1 .75-.75h6.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1-.75-.75M2.75 7a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5z");
}

</style>
