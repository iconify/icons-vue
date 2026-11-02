<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4nd5ibfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:expand-fill-round" /></template>
<style>
.o4nd5ibfn {
  fill: currentColor;
  d: path("M20 3a1 1 0 0 1 1 1v6a1 1 0 0 1-2 0V5h-5a1 1 0 0 1 0-2ZM4 21a1 1 0 0 1-1-1v-6a1 1 0 0 1 2 0v5h5a1 1 0 0 1 0 2Z");
}

</style>
