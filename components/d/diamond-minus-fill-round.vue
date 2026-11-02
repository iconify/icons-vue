<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fodpyfbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-minus-fill-round" /></template>
<style>
.fodpyfbhh {
  fill: currentColor;
  d: path("m17.707 18.707l-2 2a5.243 5.243 0 0 1-7.414 0l-5-5a5.243 5.243 0 0 1 0-7.414l5-5a5.243 5.243 0 0 1 7.414 0l5 5a5.243 5.243 0 0 1 0 7.414ZM15 11H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
