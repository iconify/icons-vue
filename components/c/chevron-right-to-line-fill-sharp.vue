<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="litsavbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-right-to-line-fill-sharp" /></template>
<style>
.litsavbfc {
  fill: currentColor;
  d: path("M18 18a1 1 0 0 1-2 0V6a1 1 0 0 1 2 0Zm-11.707-.707L11.586 12L6.293 6.707a.999.999 0 1 1 1.414-1.414l6 6a1 1 0 0 1 0 1.414l-6 6a.999.999 0 1 1-1.414-1.414");
}

</style>
