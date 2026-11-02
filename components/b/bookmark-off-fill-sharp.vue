<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yay3gb24s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bookmark-off-fill-sharp" /></template>
<style>
.yay3gb24s {
  fill: currentColor;
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414L19 19.414V20a1 1 0 0 1-1.555.832L12 17.202l-5.445 3.63A1 1 0 0 1 5 20V5.414L2.293 2.707a.999.999 0 1 1 1.414-1.414M8.243 3H18a1 1 0 0 1 1 1v9.757Z");
}

</style>
