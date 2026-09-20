<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d33znabhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-square-outline-sharp" /></template>
<style>
.d33znabhl {
  fill: currentColor;
  d: path("M13.577 14.923h5.846V9.077h-5.846zm-1 1V12.5h-9.5v-1h9.5V8.077h7.846v7.846zM16.5 12");
}

</style>
