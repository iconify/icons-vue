<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ect-16b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:black-heart" /></template>
<style>
.ect-16b2h {
  fill: currentColor;
  d: path("M61.072 18.16c-6.395-16.919-27.154-9.328-29.074-.879c-2.64-9.004-22.89-15.721-29.07.891C-3.953 36.674 29.598 53.279 31.999 56c2.397-2.162 35.951-19.639 29.073-37.84");
}

</style>
