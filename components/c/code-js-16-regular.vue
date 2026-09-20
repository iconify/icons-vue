<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="op-n8kbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-js-16-regular" /></template>
<style>
.op-n8kbtc {
  fill: currentColor;
  d: path("M7 4.5v5a2.5 2.5 0 0 1-5 0V9a.5.5 0 0 1 1 0v.5a1.5 1.5 0 1 0 3 0v-5a.5.5 0 0 1 1 0m3.676 3.033C9.633 7.142 9 6.86 9 6.25C9 5.328 9.808 5 10.5 5s1.5.327 1.5 1.25a.5.5 0 0 0 1 0a2.28 2.28 0 0 0-1.567-2.146a3.2 3.2 0 0 0-1.866 0A2.28 2.28 0 0 0 8 6.25c0 1.347 1.289 1.83 2.324 2.218S12 9.142 12 9.75c0 .923-.808 1.25-1.5 1.25S9 10.674 9 9.75a.5.5 0 0 0-1 0A2.28 2.28 0 0 0 10.5 12A2.28 2.28 0 0 0 13 9.75c0-1.35-1.289-1.83-2.324-2.218");
}

</style>
