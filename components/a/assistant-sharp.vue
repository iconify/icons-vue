<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y437t3bqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:assistant-sharp" /></template>
<style>
.y437t3bqn {
  fill: currentColor;
  d: path("m12 23l-3-3H3V2h18v18h-6l-3 3Zm1.55-10.45L17 11l-3.45-1.55L12 6l-1.55 3.45L7 11l3.45 1.55L12 16l1.55-3.45Z");
}

</style>
