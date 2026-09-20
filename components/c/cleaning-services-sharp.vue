<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q41xylf6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cleaning-services-sharp" /></template>
<style>
.q41xylf6v {
  fill: currentColor;
  d: path("M3 23V11h6V1h6v10h6v12zm2-2h2v-4h2v4h2v-4h2v4h2v-4h2v4h2v-8H5z");
}

</style>
