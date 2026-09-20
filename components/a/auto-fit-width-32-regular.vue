<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mf8k_z5mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:auto-fit-width-32-regular" /></template>
<style>
.mf8k_z5mw {
  fill: currentColor;
  d: path("M4 6a1 1 0 0 1 1 1v18a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1m24 0a1 1 0 0 1 1 1v18a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1m-8.707 5.293a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 .068 1.338l-.068.076l-4 4l-.076.068a1 1 0 0 1-1.406-1.406l.068-.076L21.586 17H10.414l2.293 2.293a1 1 0 1 1-1.414 1.414l-4-4l-.066-.073a1 1 0 0 1 .066-1.341l4-4l.076-.068a1 1 0 0 1 1.406 1.406l-.068.076L10.414 15h11.172l-2.293-2.293a1 1 0 0 1 0-1.414");
}

</style>
