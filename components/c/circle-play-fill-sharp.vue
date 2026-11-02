<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk8uq6x_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-play-fill-sharp" /></template>
<style>
.uk8uq6x_o {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M9 8v8a1 1 0 0 0 1.555.832l6-4a1 1 0 0 0 0-1.664l-6-4A1 1 0 0 0 9 8");
}

</style>
