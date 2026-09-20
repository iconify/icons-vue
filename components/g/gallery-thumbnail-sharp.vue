<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgm09us_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:gallery-thumbnail-sharp" /></template>
<style>
.pgm09us_e {
  fill: currentColor;
  d: path("M1 19V5h14v14zm16-8V5h6v6zM4 15h8l-2.625-3.5L7.5 14l-1.375-1.825zm13 4v-6h6v6z");
}

</style>
