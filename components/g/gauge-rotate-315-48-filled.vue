<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kkxhmubuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-48-filled" /></template>
<style>
.kkxhmubuz {
  fill: currentColor;
  d: path("M25.62 4.064C35.91 4.89 44 13.5 44 24c0 11.045-8.954 20-20 20S4 35.045 4 24A19.95 19.95 0 0 1 9.946 9.77a1.5 1.5 0 0 1 2.108 2.134A16.95 16.95 0 0 0 7 24c0 9.389 7.611 17 17 17s17-7.611 17-17c0-8.924-6.877-16.244-15.62-16.945a1.5 1.5 0 0 1 .24-2.99M13.776 16.117c-.771-1.489.854-3.114 2.343-2.342l.149.086c3.372 2.149 6.767 4.272 10.052 6.554c.842.585 1.586 1.126 1.923 1.463a4.5 4.5 0 0 1-6.363 6.364c-.337-.337-.879-1.082-1.464-1.924c-1.852-2.665-4.894-7.434-6.553-10.052z");
}

</style>
