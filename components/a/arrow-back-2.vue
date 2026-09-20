<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my5a9-bfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-back-2" /></template>
<style>
.my5a9-bfk {
  fill: currentColor;
  d: path("M16 19L5 12l11-7z");
}

</style>
