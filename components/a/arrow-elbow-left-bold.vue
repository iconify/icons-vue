<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kq-upibsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-left-bold" /></template>
<style>
.kq-upibsw {
  fill: currentColor;
  d: path("m240.49 104.49l-96 96a12 12 0 0 1-17 0L36 109v43a12 12 0 0 1-24 0V80a12 12 0 0 1 12-12h72a12 12 0 0 1 0 24H53l83 83l87.51-87.52a12 12 0 0 1 17 17Z");
}

</style>
