<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nw2f66bgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fitbit-arrow-downward" /></template>
<style>
.nw2f66bgg {
  fill: currentColor;
  d: path("m12 18l-6-6l1.4-1.4l3.6 3.575V6h2v8.175l3.6-3.575L18 12l-6 6Z");
}

</style>
