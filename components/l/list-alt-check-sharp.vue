<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4q4lrb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:list-alt-check-sharp" /></template>
<style>
.q4q4lrb9g {
  fill: currentColor;
  d: path("M4 20V4h16v9.489l-2.746 2.746l-2.029-2.03l-4.096 4.072L12.852 20zm3.346-7.23h1.538v-1.54H7.346zm0-3.77h1.538V7.462H7.346zm3.846 3.5h5.385v-1h-5.385zm0-3.77h5.385v-1h-5.385zM17.254 21l-2.742-2.723l.713-.708l2.029 2.029l4.057-4.057l.708.713z");
}

</style>
