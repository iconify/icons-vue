<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6jjg6bsr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-drive-fill-sharp" /></template>
<style>
.j6jjg6bsr {
  fill: currentColor;
  d: path("m17.894 4.553l4 8c.07.139.106.292.106.447v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6c0-.155.036-.308.106-.447l4-8A1 1 0 0 1 7 4h10c.379 0 .725.214.894.553M16.382 6H7.618l-3 6h14.764ZM6 16a1 1 0 1 0 2 0a1 1 0 0 0-2 0m4 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
