<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-356bbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-100-24-filled" /></template>
<style>
.p-356bbkx {
  fill: currentColor;
  d: path("M12 8V2H6a2 2 0 0 0-2 2v10.228c.338.197.679.514.862.971a3.498 3.498 0 0 1 5.638.497A3.5 3.5 0 0 1 17 17.5v2a3.5 3.5 0 0 1-1.05 2.5H18a2 2 0 0 0 2-2V10h-6a2 2 0 0 1-2-2m1.5 0V2.5l6 6H14a.5.5 0 0 1-.5-.5m-6 7A2.5 2.5 0 0 0 5 17.5v2a2.5 2.5 0 0 0 5 0v-2A2.5 2.5 0 0 0 7.5 15m-1 2.5a1 1 0 1 1 2 0v2a1 1 0 1 1-2 0zm4.5 0a2.5 2.5 0 0 1 5 0v2a2.5 2.5 0 0 1-5 0zm2.5-1a1 1 0 0 0-1 1v2a1 1 0 1 0 2 0v-2a1 1 0 0 0-1-1M4 15.938c0-.562-.433-.864-.742-.951s-.804-.056-1.11.371c-.318.443-.76.939-1.28 1.247a.75.75 0 0 0 .764 1.29c.323-.19.613-.42.868-.662v4.017a.75.75 0 0 0 1.5 0z");
}

</style>
