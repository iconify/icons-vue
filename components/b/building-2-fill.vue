<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr176ibxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-fill" /></template>
<style>
.zr176ibxe {
  fill: currentColor;
  d: path("M21 21H3a1 1 0 0 1 0-2h1V6a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v2.802a2.42 2.42 0 0 1 2.707.491l3 3C19.422 13.008 20 13.961 20 15v4h1a1 1 0 0 1 0 2m-8-9.586V19h5v-4c0-.468-.395-.98-.707-1.293l-3-3a.414.414 0 0 0-.586 0Z");
}

</style>
