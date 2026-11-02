<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0jc5rbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-check-fill-sharp" /></template>
<style>
.j0jc5rbnc {
  fill: currentColor;
  d: path("M3 5h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 5h11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m12.707 4.293L17 15.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M3 15h7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
