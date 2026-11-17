<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-juroxlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-up-fill-sharp" /></template>
<style>
.v-juroxlz {
  fill: currentColor;
  d: path("M20 20a1.002 1.002 0 0 1-1.707.707L12 14.414l-6.293 6.293A1 1 0 0 1 4 20v-9c0-.265.105-.52.293-.707l7-7a1 1 0 0 1 1.414 0l7 7A1 1 0 0 1 20 11Z");
}

</style>
