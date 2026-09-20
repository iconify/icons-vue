<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ea5s6n3cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bounce-48-regular" /></template>
<style>
.ea5s6n3cp {
  fill: currentColor;
  d: path("M4 14.25c0-.69.56-1.25 1.25-1.25h15.5a1.25 1.25 0 1 1 0 2.5H8.295l16.706 16.494L41.872 15.36a1.25 1.25 0 1 1 1.756 1.78l-17.75 17.5a1.25 1.25 0 0 1-1.756 0L6.5 17.24v12.577a1.25 1.25 0 1 1-2.5 0z");
}

</style>
