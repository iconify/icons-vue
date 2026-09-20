<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="wutxhfb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-0-28-regular" /></template>
<style>
.wutxhfb7w {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12s-5.373 12-12 12S2 20.627 2 14S7.373 2 14 2m0 1.5C8.201 3.5 3.5 8.201 3.5 14S8.201 24.5 14 24.5S24.5 19.799 24.5 14S19.799 3.5 14 3.5m-.976 2.796c.215-1.027 1.638-1.059 1.927-.096l.025.096c.468 2.273.955 4.544 1.345 6.832c.1.585.179 1.11.179 1.374a2.5 2.5 0 0 1-5 0c0-.263.08-.79.179-1.374c.316-1.856.985-5.107 1.345-6.832");
}

</style>
