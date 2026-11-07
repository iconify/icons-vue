<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih0ltu27k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-off-fill-round" /></template>
<style>
.ih0ltu27k {
  fill: currentColor;
  d: path("m7.476 4.234l-.746-.747l3.942-1.946a3 3 0 0 1 1.312-.31h.032c.456.002.904.108 1.312.31L20.333 5q.311.154.579.373L12.68 9.438ZM2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-2.468-2.468l-4.501 2.222a3 3 0 0 1-.324.138v-7.185l-2-2v9.185a3 3 0 0 1-.324-.137l-.004-.003l-7-3.456A3 3 0 0 1 2 16.313V7.687q0-.299.057-.593l5.182 2.559l-5.946-5.946a.999.999 0 1 1 1.414-1.414m11.466 8.638l7.77-3.837q.057.294.057.593v8.626a3.02 3.02 0 0 1-.619 1.826Z");
}

</style>
