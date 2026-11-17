<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwfo4sblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:leaf-fill-round" /></template>
<style>
.wwfo4sblf {
  fill: currentColor;
  d: path("m4 20l1.497-1.497l.003-.003l7.002-7.002a1 1 0 0 0-1.416-1.412L5.331 15.84c-1.616-4.098-.406-8.014 3.495-10.201a12.5 12.5 0 0 1 2.833-1.135c2.413-.656 4.953-.725 7.432-.5c.48.044.861.425.905.905c.225 2.479.156 5.019-.5 7.432c-.507 1.863-1.392 3.671-2.809 5.011c-2.395 2.261-5.542 2.489-8.513 1.322l-2.75 2.75a1 1 0 0 1-1.414 0l-.01-.01A1 1 0 0 1 4 20");
}

</style>
