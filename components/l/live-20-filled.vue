<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="utth4x6zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:live-20-filled" /></template>
<style>
.utth4x6zg {
  fill: currentColor;
  d: path("M4.342 4.343a.75.75 0 0 1 1.06 1.06a6.5 6.5 0 0 0 0 9.193a.75.75 0 0 1-1.06 1.06a8 8 0 0 1 0-11.313m10.253 0a.75.75 0 0 1 1.06 0a8 8 0 0 1 0 11.314a.75.75 0 1 1-1.06-1.061a6.5 6.5 0 0 0 0-9.192a.75.75 0 0 1 0-1.061M6.463 6.464a.75.75 0 0 1 1.061 1.06a3.5 3.5 0 0 0 0 4.95a.75.75 0 0 1-1.06 1.061a5 5 0 0 1 0-7.07m6.01 0a.75.75 0 0 1 1.06 0a5 5 0 0 1 0 7.071a.75.75 0 0 1-1.06-1.06a3.5 3.5 0 0 0 0-4.95a.75.75 0 0 1 0-1.06M10 8.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
