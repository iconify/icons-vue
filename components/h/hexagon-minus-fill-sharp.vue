<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uki8hy1jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hexagon-minus-fill-sharp" /></template>
<style>
.uki8hy1jp {
  fill: currentColor;
  d: path("M20.447 6.106A1 1 0 0 1 21 7v10a1 1 0 0 1-.553.894l-8 4a1 1 0 0 1-.894 0l-8-4A1 1 0 0 1 3 17V7c0-.379.214-.725.553-.894l8-4a1 1 0 0 1 .894 0ZM9 11a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Z");
}

</style>
