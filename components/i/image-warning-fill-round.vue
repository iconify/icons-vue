<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7bpnrb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-warning-fill-round" /></template>
<style>
.p7bpnrb9q {
  fill: currentColor;
  d: path("m17.399 21.985l-6.692-6.692a5.24 5.24 0 0 0-7.414 0L2 16.586V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-4.601 4.985M16 6a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm-.99 5H15a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M3.191 18.224l1.516-1.517a3.243 3.243 0 0 1 4.586 0L14.586 22H7a4.99 4.99 0 0 1-4.584-3.001Z");
}

</style>
