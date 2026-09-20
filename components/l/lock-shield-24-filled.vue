<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7pa56bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-24-filled" /></template>
<style>
.o7pa56bfi {
  fill: currentColor;
  d: path("M18.01 12.194a.713.713 0 0 1 .98 0c.652.651 1.907 1.686 3.45 1.899c.307.042.56.285.56.589v2.838c0 3.816-3.58 5.2-4.353 5.456a.46.46 0 0 1-.293 0C17.578 22.72 14 21.336 14 17.52v-2.838c0-.304.253-.547.56-.59c1.543-.212 2.798-1.247 3.45-1.898M12 1a5 5 0 0 1 5 5v2.01a3.25 3.25 0 0 1 3 3.24v.526a8 8 0 0 1-.31-.289a1.71 1.71 0 0 0-2.39 0c-.53.53-1.61 1.44-2.88 1.62c-.59.085-1.208.52-1.375 1.208A1.248 1.248 0 0 0 10.75 15a1.25 1.25 0 0 0 2.25.747v1.776c0 1.72.64 3.257 1.857 4.477H7.25A3.25 3.25 0 0 1 4 18.75v-7.5a3.25 3.25 0 0 1 3-3.24V6a5 5 0 0 1 5-5m0 1.5A3.5 3.5 0 0 0 8.5 6v2h7V6A3.5 3.5 0 0 0 12 2.5");
}

</style>
