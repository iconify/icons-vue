<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n25m17m-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-object-outline-sharp" /></template>
<style>
.n25m17m-z {
  fill: currentColor;
  d: path("M14 20v-2h4v-5.675h2v-.65h-2V6h-4V4h6v5.85h2v4.3h-2V20zM4 20v-5.85H2v-4.3h2V4h6v2H6v5.675H4v.65h2V18h4v2z");
}

</style>
