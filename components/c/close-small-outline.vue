<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niz638s_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:close-small-outline" /></template>
<style>
.niz638s_o {
  fill: currentColor;
  d: path("M8.4 17L7 15.6l3.6-3.6L7 8.425l1.4-1.4l3.6 3.6l3.575-3.6l1.4 1.4l-3.6 3.575l3.6 3.6l-1.4 1.4L12 13.4z");
}

</style>
