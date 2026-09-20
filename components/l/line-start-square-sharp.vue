<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh36n-rss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-start-square-sharp" /></template>
<style>
.dh36n-rss {
  fill: currentColor;
  d: path("M13 17.5H2v-11h11V11h9v2h-9z");
}

</style>
