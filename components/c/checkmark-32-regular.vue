<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v2cog3b-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-32-regular" /></template>
<style>
.v2cog3b-n {
  fill: currentColor;
  d: path("M29.726 5.312a1 1 0 0 1-.038 1.414l-19 18a1 1 0 0 1-1.42-.044l-7-7.5a1 1 0 1 1 1.463-1.364l6.313 6.763L28.312 5.274a1 1 0 0 1 1.414.038");
}

</style>
