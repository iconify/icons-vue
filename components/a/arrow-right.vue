<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt594-ldn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-right" /></template>
<style>
.wt594-ldn {
  fill: currentColor;
  d: path("M10.5 15.808V8.192L14.308 12z");
}

</style>
