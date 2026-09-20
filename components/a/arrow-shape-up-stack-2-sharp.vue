<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt2u2n6lj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-shape-up-stack-2-sharp" /></template>
<style>
.tt2u2n6lj {
  fill: currentColor;
  d: path("M9.462 22v-2.98H5l7-7.5l7 7.5h-4.462V22zM5 14.27l7-7.5l7 7.5h-1.367L12 8.25l-5.633 6.02zm0-4.75l7-7.5l7 7.5h-1.367L12 3.5L6.367 9.52z");
}

</style>
