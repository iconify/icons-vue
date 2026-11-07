<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-68pjb7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-off-fill-round" /></template>
<style>
.l-68pjb7l {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414l-2.903-2.902c-.452.13-.92.196-1.39.195H7a5 5 0 0 1-5-5V9a4.98 4.98 0 0 1 1.769-3.817L1.293 2.707a.999.999 0 1 1 1.414-1.414m11.707 8.879L8.243 4H17c.981 0 1.94.286 2.758.828Zm6.032-3.204l.726-.726A5 5 0 0 1 22 9v6a5 5 0 0 1-.525 2.233l-5.647-5.647Z");
}

</style>
