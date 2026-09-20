<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grtip6mmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:elevation-outline" /></template>
<style>
.grtip6mmu {
  fill: currentColor;
  d: path("m2.05 21l6.45-9h5.05L21 3.3V21zm1.75-5.825l-1.6-1.15L6.5 8h5.05l4.7-5.475l1.5 1.3L12.45 10H7.5zM5.95 19H19V8.7L14.45 14H9.5zM19 19");
}

</style>
