<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osh68j76k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-search-fill-round" /></template>
<style>
.osh68j76k {
  fill: currentColor;
  d: path("m17.399 21.985l-6.692-6.692a5.24 5.24 0 0 0-7.414 0L2 16.586V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-4.601 4.985m-2.106-11.277l2 1.999a.999.999 0 1 0 1.414-1.414l-1.999-2a3 3 0 1 0-1.415 1.415M3.191 18.224l1.516-1.517a3.243 3.243 0 0 1 4.586 0L14.586 22H7a4.99 4.99 0 0 1-4.584-3.001Z");
}

</style>
