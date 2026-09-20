<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6cgbeyyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:image-inset-sharp" /></template>
<style>
.y6cgbeyyn {
  fill: currentColor;
  d: path("M6 16h12V8H6zm2-2l2.125-2.825L11.5 13l1.875-2.5L16 14zm-6 6V4h20v16z");
}

</style>
