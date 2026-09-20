<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q6z52n_kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-12-filled" /></template>
<style>
.q6z52n_kh {
  fill: currentColor;
  d: path("M6 1.75a.75.75 0 0 1 .75.75v2.75H9.5a.75.75 0 0 1 0 1.5H6.75V9.5a.75.75 0 0 1-1.5 0V6.75H2.5a.75.75 0 0 1 0-1.5h2.75V2.5A.75.75 0 0 1 6 1.75");
}

</style>
