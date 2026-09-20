<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zgctp7bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-48-regular" /></template>
<style>
.zgctp7bqc {
  fill: currentColor;
  d: path("M24 4a9 9 0 0 1 9 9v5.006a6.25 6.25 0 0 1 6 6.244v13.5A6.25 6.25 0 0 1 32.75 44h-17.5A6.25 6.25 0 0 1 9 37.75v-13.5a6.25 6.25 0 0 1 6-6.244V13a9 9 0 0 1 9-9m-8.75 16.5a3.75 3.75 0 0 0-3.75 3.75v13.5a3.75 3.75 0 0 0 3.75 3.75h17.5a3.75 3.75 0 0 0 3.75-3.75v-13.5a3.75 3.75 0 0 0-3.75-3.75zm8.75 8a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m0-22a6.5 6.5 0 0 0-6.5 6.5v5h13v-5A6.5 6.5 0 0 0 24 6.5");
}

</style>
