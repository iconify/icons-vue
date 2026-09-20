<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldyxs_b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:forest-outline" /></template>
<style>
.ldyxs_b6e {
  fill: currentColor;
  d: path("M7 22v-4H0l3.85-6H2L9 2l3 4.3L15 2l7 10h-1.85L24 18h-7v4h-4v-4h-2v4zm9.725-6h3.625l-3.875-6h1.675L15 5.5l-1.775 2.525L16 12h-1.85zM3.65 16h10.7l-3.875-6h1.675L9 5.5L5.85 10h1.675zm0 0h3.875H5.85h6.3h-1.675h3.875zm13.075 0H14.15H16h-2.775h4.925h-1.675h3.875zM13 18h4zm5.025 0");
}

</style>
