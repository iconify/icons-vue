<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xlwfgmb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:javascript-16-filled" /></template>
<style>
.xlwfgmb_g {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM7.5 6a.5.5 0 0 0-.5.5v4a.5.5 0 0 1-.5.5h-1a.5.5 0 0 0 0 1h1A1.5 1.5 0 0 0 8 10.5v-4a.5.5 0 0 0-.5-.5m1 1.5V8A1.5 1.5 0 0 0 10 9.5h.5a.5.5 0 0 1 .5.5v.5a.5.5 0 0 1-.5.5H9a.5.5 0 0 0 0 1h1.5a1.5 1.5 0 0 0 1.5-1.5V10a1.5 1.5 0 0 0-1.5-1.5H10a.5.5 0 0 1-.5-.5v-.5A.5.5 0 0 1 10 7h1.5a.5.5 0 0 0 0-1H10a1.5 1.5 0 0 0-1.5 1.5");
}

</style>
