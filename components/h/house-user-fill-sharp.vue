<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep9w6q2su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-fill-sharp" /></template>
<style>
.ep9w6q2su {
  fill: currentColor;
  d: path("M20 22H4a1 1 0 0 1-1-1V11c0-.265.105-.52.293-.707l8-8a1 1 0 0 1 1.414 0l8 8A1 1 0 0 1 21 11v10a1 1 0 0 1-1 1M9.236 9.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M16.901 20a5.003 5.003 0 0 0-9.802 0Z");
}

</style>
