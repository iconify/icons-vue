<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdcn6t91n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:4g-mobiledata-outline-sharp" /></template>
<style>
.bdcn6t91n {
  fill: currentColor;
  d: path("M7 17v-3H3V7h2v5h2V7h2v5h2v2H9v3zm5 0V7h9v2h-7v6h5v-2h-2.5v-2H21v6z");
}

</style>
