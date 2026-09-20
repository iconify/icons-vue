<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f3_2_2bnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-one-third-right-hint-16-regular" /></template>
<style>
.f3_2_2bnx {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5a.5.5 0 0 0 1 0A1.5 1.5 0 0 1 4.5 3a.5.5 0 0 0 0-1M7 2a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zM3 7a.5.5 0 0 0-1 0v2a.5.5 0 0 0 1 0zm0 4.5a.5.5 0 0 0-1 0A2.5 2.5 0 0 0 4.5 14a.5.5 0 0 0 0-1A1.5 1.5 0 0 1 3 11.5M7 13a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1zm3-11a.5.5 0 0 0-.5.5v11a.5.5 0 0 0 .5.5h1.5a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zm.5 11V3h1A1.5 1.5 0 0 1 13 4.5v7a1.5 1.5 0 0 1-1.5 1.5z");
}

</style>
