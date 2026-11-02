<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hflhkvb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-alt-2-fill" /></template>
<style>
.hflhkvb9l {
  fill: currentColor;
  d: path("M4 12c0-1.039.578-1.992 1.293-2.707l5-5a2.414 2.414 0 0 1 3.414 0l5 5C19.422 10.008 20 10.961 20 12v7h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1Zm6 7h4v-3a2 2 0 1 0-4 0Z");
}

</style>
