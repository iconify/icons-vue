<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-k0v4ixy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:headphones-battery-sharp" /></template>
<style>
.y-k0v4ixy {
  fill: currentColor;
  d: path("M2 18v-6q0-2.5 1.75-4.25T8 6t4.25 1.75T14 12v6h-4v-5h2.5v-1q0-1.875-1.312-3.187T8 7.5T4.813 8.813T3.5 12v1H6v5zm14 0V7h2V6h2v1h2v11z");
}

</style>
