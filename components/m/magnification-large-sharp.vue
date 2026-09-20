<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msn5gdzzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:magnification-large-sharp" /></template>
<style>
.msn5gdzzt {
  fill: currentColor;
  d: path("M5 15h12V7H5zm-3 5V4h20v16z");
}

</style>
