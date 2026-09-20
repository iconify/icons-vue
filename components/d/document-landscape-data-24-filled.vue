<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4fp1vfbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-landscape-data-24-filled" /></template>
<style>
.t4fp1vfbz {
  fill: currentColor;
  d: path("M2 6.75A2.75 2.75 0 0 1 4.75 4h14.5A2.75 2.75 0 0 1 22 6.75v10.5A2.75 2.75 0 0 1 19.25 20H4.75A2.75 2.75 0 0 1 2 17.25zM12 7a2 2 0 0 0-2 2v6a2 2 0 1 0 4 0V9a2 2 0 0 0-2-2m-5 5a2 2 0 0 0-2 2v1a2 2 0 1 0 4 0v-1a2 2 0 0 0-2-2m8 0v3a2 2 0 1 0 4 0v-3a2 2 0 1 0-4 0");
}

</style>
