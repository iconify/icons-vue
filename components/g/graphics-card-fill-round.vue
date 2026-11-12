<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9tielmvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:graphics-card-fill-round" /></template>
<style>
.n9tielmvn {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 2 0v1.535A4 4 0 0 1 6 4h12a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4v2a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-2a4 4 0 0 1-2-.535V21a1 1 0 0 1-2 0Zm3.236 6.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335m8 0a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M8 20h8v-2H8Z");
}

</style>
