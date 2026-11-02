<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1jqh6bvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-fill-sharp" /></template>
<style>
.x1jqh6bvp {
  fill: currentColor;
  d: path("M19.707 10.293A1 1 0 0 1 20 11v8h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1v-8c0-.265.105-.52.293-.707l7-7a1 1 0 0 1 1.414 0ZM10 19h4v-3a2 2 0 1 0-4 0Z");
}

</style>
