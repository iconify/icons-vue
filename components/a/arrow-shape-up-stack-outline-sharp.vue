<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqyg5gbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-shape-up-stack-outline-sharp" /></template>
<style>
.vqyg5gbks {
  fill: currentColor;
  d: path("M9.462 19v-2.98H5l7-7.5l7 7.5h-4.462V19zm1-.98h3.076v-3h3.146l-4.684-5l-4.684 5h3.146zM5 11.27l7-7.5l7 7.5h-1.367L12 5.25l-5.633 6.02zm7 3.75");
}

</style>
