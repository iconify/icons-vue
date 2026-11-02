<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_i2tgbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-fill-sharp" /></template>
<style>
.l_i2tgbwf {
  fill: currentColor;
  d: path("M3 17v-2c0-.39.098-.773.299-1.108c.133-.222.312-.417.494-.599c.065-.066.145-.133.193-.214C4 13.057 4 13.026 4 13v-3a8 8 0 0 1 16 0v3c0 .026 0 .057.014.079c.048.081.128.148.193.214c.182.182.361.377.494.599c.201.335.299.718.299 1.108v2a1 1 0 0 1-1 1h-4a4 4 0 0 1-8 0H4a1 1 0 0 1-1-1");
}

</style>
