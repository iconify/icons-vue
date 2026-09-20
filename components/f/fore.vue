<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i505rwb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fore" /></template>
<style>
.i505rwb9n {
  d: path("M5.172 3h13.656v3.724H5.172zm0 8.069h12.414v3.724h-8.69V21H5.173z");
}

</style>
