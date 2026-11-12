<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zidkatfhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-fill-round" /></template>
<style>
.zidkatfhk {
  fill: currentColor;
  d: path("M16 22H8a5 5 0 0 1-5-5v-4c0-1.317.335-2.748 1.293-3.707l4-4a5.243 5.243 0 0 1 7.414 0l4 4C20.665 10.252 21 11.683 21 13v4a5 5 0 0 1-5 5M9.236 9.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335m7.637 10.04a5.003 5.003 0 0 0-9.746 0A3 3 0 0 0 8 20h8a3 3 0 0 0 .873-.128");
}

</style>
