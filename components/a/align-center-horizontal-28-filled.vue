<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="owl83ac6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-center-horizontal-28-filled" /></template>
<style>
.owl83ac6y {
  fill: currentColor;
  d: path("M26 13.75a.75.75 0 0 1-.75.75H23V18a2.75 2.75 0 0 1-2.75 2.75h-2.5A2.75 2.75 0 0 1 15 18v-3.5h-2v6.25a2.75 2.75 0 0 1-2.75 2.75h-2.5A2.75 2.75 0 0 1 5 20.75V14.5H2.75a.75.75 0 0 1 0-1.5H5V7.25A2.75 2.75 0 0 1 7.75 4.5h2.5A2.75 2.75 0 0 1 13 7.25V13h2v-3a2.75 2.75 0 0 1 2.75-2.75h2.5A2.75 2.75 0 0 1 23 10v3h2.25a.75.75 0 0 1 .75.75");
}

</style>
