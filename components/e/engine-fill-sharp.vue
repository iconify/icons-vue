<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_dapccjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:engine-fill-sharp" /></template>
<style>
.l_dapccjp {
  fill: currentColor;
  d: path("M13 3a1 1 0 0 1 0 2h-1v2h1c.379 0 .725.214.894.553L15.618 11H17v-1a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1v-1h-2v3a1 1 0 0 1-1 1h-4a1 1 0 0 1-.894-.553L7.382 17H6a1 1 0 0 1-1-1v-2H4v1a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0v1h1v-1c0-.265.105-.52.293-.707l3-3A1 1 0 0 1 9 7h1V5H9a1 1 0 0 1 0-2Z");
}

</style>
