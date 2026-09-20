<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-ef35b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-shape-up-stack" /></template>
<style>
.d-ef35b5l {
  fill: currentColor;
  d: path("M9.462 19v-2.98H5l7-7.5l7 7.5h-4.462V19zM5 11.27l7-7.5l7 7.5h-1.367L12 5.25l-5.633 6.02z");
}

</style>
