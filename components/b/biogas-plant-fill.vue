<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3murfgzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:biogas-plant-fill" /></template>
<style>
.o3murfgzl {
  fill: currentColor;
  d: path("M14.798 9c.431.611.764 1.286.985 2H2.217a7.1 7.1 0 0 1 6.39-4.989a7.1 7.1 0 0 1 13.376 1.808l.001.001q.015.084.016.17V16a2 2 0 0 1-2 2h-4v2a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-7h14v3h4V9Zm-2.163-2h7.014a5.101 5.101 0 0 0-8.863-.773c.649.169 1.272.43 1.849.773");
}

</style>
