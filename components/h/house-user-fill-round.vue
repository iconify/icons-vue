<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brlyj-bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-fill-round" /></template>
<style>
.brlyj-bbd {
  fill: currentColor;
  d: path("M16 22H8a5 5 0 0 1-5-5v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l4 3.5A5 5 0 0 1 21 11.815V17a5 5 0 0 1-5 5M9.236 9.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335m7.637 10.04a5.003 5.003 0 0 0-9.746 0A3 3 0 0 0 8 20h8a3 3 0 0 0 .873-.128");
}

</style>
