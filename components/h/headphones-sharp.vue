<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdy8_bb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:headphones-sharp" /></template>
<style>
.tdy8_bb5y {
  fill: currentColor;
  d: path("M9 21H3v-9q0-1.875.713-3.512t1.924-2.85t2.85-1.925T12 3t3.513.713t2.85 1.924t1.925 2.85T21 12v9h-6v-8h4v-1q0-2.925-2.037-4.962T12 5T7.038 7.038T5 12v1h4z");
}

</style>
