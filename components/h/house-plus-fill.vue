<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z53tg2bhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-plus-fill" /></template>
<style>
.z53tg2bhe {
  fill: currentColor;
  d: path("M3 19v-7c0-1.039.578-1.992 1.293-2.707l6-6a2.414 2.414 0 0 1 3.414 0l6 6C20.422 10.008 21 10.961 21 12v7a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3m12-6h-2v-2a1 1 0 0 0-2 0v2H9a1 1 0 0 0 0 2h2v2a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2");
}

</style>
