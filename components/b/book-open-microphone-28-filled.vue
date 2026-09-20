<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="k61mulb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-28-filled" /></template>
<style>
.k61mulb_d {
  fill: currentColor;
  d: path("M25.75 19.25a.75.75 0 0 1 .75.75a5 5 0 0 1-4.25 4.943v1.307a.75.75 0 0 1-1.5 0v-1.307A5 5 0 0 1 16.5 20a.75.75 0 0 1 1.5 0a3.5 3.5 0 1 0 7 0a.75.75 0 0 1 .75-.75M11.5 4c.98 0 1.865.402 2.5 1.05A3.5 3.5 0 0 1 16.5 4H24a2 2 0 0 1 2 2v12.27a1.74 1.74 0 0 0-1 .15V16.5c0-.953-.382-1.817-1-2.448V6h-7.5A1.5 1.5 0 0 0 15 7.5v13a1.5 1.5 0 0 0 .781 1.316c.26.818.69 1.56 1.248 2.184H16.5a3.5 3.5 0 0 1-2.5-1.05A3.5 3.5 0 0 1 11.5 24H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zm10 10a2.5 2.5 0 0 1 2.5 2.5V20a2.5 2.5 0 0 1-5 0v-3.5a2.5 2.5 0 0 1 2.5-2.5M4 22h7.5a1.5 1.5 0 0 0 1.5-1.5v-13A1.5 1.5 0 0 0 11.5 6H4z");
}

</style>
