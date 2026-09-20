<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sghx99bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-arrow-up-24-regular" /></template>
<style>
.sghx99bhl {
  fill: currentColor;
  d: path("M6.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m5.672-10c.53 0 1.04.21 1.415.586l5.827 5.827c.375.375.586.885.586 1.415V20a2 2 0 0 1-2 2h-6.812a6.5 6.5 0 0 0 1.079-1.5H18a.5.5 0 0 0 .5-.5V10H14a2 2 0 0 1-2-2V3.5H6a.5.5 0 0 0-.5.5v7.076a6.5 6.5 0 0 0-1.5.422V4a2 2 0 0 1 2-2zM6.854 14.147a.5.5 0 0 0-.708 0l-2.5 2.5a.5.5 0 1 0 .708.707L6 15.707V20.5a.5.5 0 0 0 1 0v-4.793l1.646 1.646a.5.5 0 1 0 .708-.707zM13.5 8a.5.5 0 0 0 .5.5h3.379L13.5 4.621z");
}

</style>
