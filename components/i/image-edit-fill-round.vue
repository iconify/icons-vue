<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8miacb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-fill-round" /></template>
<style>
.n8miacb0n {
  fill: currentColor;
  d: path("m13.414 22l-6.707-6.707a2.415 2.415 0 0 0-3.414 0L2 16.586V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22Zm1.879-17.707l-5 5A1 1 0 0 0 10 10v3a1 1 0 0 0 1 1h3c.265 0 .52-.105.707-.293l5-5A1 1 0 0 0 20 8.001v-.002a1 1 0 0 0-.293-.706l-3-3a1 1 0 0 0-1.414 0M3.191 18.224l1.516-1.517a.414.414 0 0 1 .586 0L10.586 22H7a4.99 4.99 0 0 1-4.584-3.001Z");
}

</style>
