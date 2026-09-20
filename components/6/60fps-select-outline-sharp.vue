<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgelcxtak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:60fps-select-outline-sharp" /></template>
<style>
.kgelcxtak {
  fill: currentColor;
  d: path("M4 14V4h7v2H6v2h5v6zm2-2h3v-2H6zm7 2V4h7v10zm2-2h3V6h-3zM3 22v-5h2v5zm4 0v-5h2v5zm4 0v-5h2v5zm4 0v-5h6v5z");
}

</style>
