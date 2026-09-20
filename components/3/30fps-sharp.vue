<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snf7v8m6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:30fps-sharp" /></template>
<style>
.snf7v8m6m {
  fill: currentColor;
  d: path("M2 19v-3h6v-2.5H2v-3h6V8H2V5h9v5.5L9.5 12l1.5 1.5V19zm13-3h4V8h-4zm-3 3V5h10v14z");
}

</style>
