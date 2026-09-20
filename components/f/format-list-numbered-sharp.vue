<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4veybybh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-list-numbered-sharp" /></template>
<style>
.r4veybybh {
  fill: currentColor;
  d: path("M4 21v-.885h2.5V18.75H5v-.885h1.5V16.5H4v-.885h3.385v2.25l-.693.52l.692.365V21zm0-6.308v-3.134h2.5v-1.366H4v-.884h3.385v3.134h-2.5v1.366h2.5v.884zm1.5-6.308v-4.5H4V3h2.385v5.385zM9.616 18.5v-1H20v1zm0-6v-1H20v1zm0-6v-1H20v1z");
}

</style>
