<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_-vckb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-center-horizontal-24-regular" /></template>
<style>
.h_-vckb6u {
  fill: currentColor;
  d: path("M21.25 12.75a.75.75 0 0 0 0-1.5H20v-2.5a2.25 2.25 0 0 0-2.25-2.25h-2.5A2.25 2.25 0 0 0 13 8.75v2.5h-2v-4.5A2.25 2.25 0 0 0 8.75 4.5h-2.5A2.25 2.25 0 0 0 4 6.75v4.5H2.75a.75.75 0 0 0 0 1.5H4v4.5a2.25 2.25 0 0 0 2.25 2.25h2.5A2.25 2.25 0 0 0 11 17.25v-4.5h2v2.5a2.25 2.25 0 0 0 2.25 2.25h2.5A2.25 2.25 0 0 0 20 15.25v-2.5zm-2.75-4v6.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1-.75-.75v-6.5a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 .75.75m-9-2v10.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 0 1-.75-.75V6.75A.75.75 0 0 1 6.25 6h2.5a.75.75 0 0 1 .75.75");
}

</style>
