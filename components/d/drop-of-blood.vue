<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="yck6cetde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:drop-of-blood" /></template>
<style>
.yck6cetde {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M28.344 17.768L18.148 1.09L8.7 17.654c-2.2 3.51-2.392 8.074-.081 11.854c3.285 5.373 10.363 7.098 15.811 3.857c5.446-3.24 7.199-10.22 3.914-15.597");
}

</style>
