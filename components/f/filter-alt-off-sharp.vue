<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhh5ssbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:filter-alt-off-sharp" /></template>
<style>
.rhh5ssbfw {
  fill: currentColor;
  d: path("M14.8 11.975L6.825 4H21.05zM19.775 22.6L14 16.825V20h-4v-7.175l-8.6-8.6L2.8 2.8l18.4 18.4z");
}

</style>
