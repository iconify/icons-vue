<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urz16m7kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-sharp" /></template>
<style>
.urz16m7kr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 2l9 4.444v11.112L12 22l-9-4.444V6.444zM3 6.444l9 4.445l9-4.445m-9 4.445V22M7.5 4.222l9 4.445");
}

</style>
