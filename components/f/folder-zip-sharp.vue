<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y14_02bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-zip-sharp" /></template>
<style>
.y14_02bqr {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm12-2h2v-2h2v-2h-2v-2h2v-2h-2V8h-2v2h2v2h-2v2h2v2h-2z");
}

</style>
