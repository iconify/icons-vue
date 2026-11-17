<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3k8_t15d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-badge-down-bulk" /></template>
<style>
.l3k8_t15d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 5v8c0 .265-.105.52-.293.707l-6 6a2.414 2.414 0 0 1-3.414 0l-6-6A1 1 0 0 1 4 13V5a1.25 1.25 0 0 1 .14-.582c.371-.712 1.242-.835 1.932-.549c.237.098.453.242.635.424l5 5a.414.414 0 0 0 .586 0l5-5c.182-.182.398-.326.635-.424c.69-.286 1.561-.163 1.932.549c.093.18.141.379.14.582");
}

</style>
