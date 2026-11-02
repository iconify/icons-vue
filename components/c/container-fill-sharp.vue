<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wn0h5fbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:container-fill-sharp" /></template>
<style>
.wn0h5fbwp {
  fill: currentColor;
  d: path("M2 5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm7 11V8a1 1 0 0 0-2 0v8a1 1 0 0 0 2 0m4 0V8a1 1 0 0 0-2 0v8a1 1 0 0 0 2 0m4-8a1 1 0 0 0-2 0v8a1 1 0 0 0 2 0Z");
}

</style>
