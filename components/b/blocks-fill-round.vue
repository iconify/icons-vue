<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpf19wolw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:blocks-fill-round" /></template>
<style>
.xpf19wolw {
  fill: currentColor;
  d: path("M17 2h2a3 3 0 0 1 3 3v2c0 .796-.316 1.559-.879 2.121A3 3 0 0 1 19 10h-2a3 3 0 0 1-3-3V5c0-.796.316-1.56.88-2.122A3 3 0 0 1 17 2m-1 3v2a1 1 0 0 0 1 1h2a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1h-2a1 1 0 0 0-1 1M2 10V8c0-.796.316-1.56.88-2.122A3 3 0 0 1 5 5h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3m5 12H5a3 3 0 0 1-3-3v-2c0-.796.316-1.56.88-2.122A3 3 0 0 1 5 14h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3m9 0h-2c-.796 0-1.56-.316-2.122-.88A3 3 0 0 1 11 19v-2a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3");
}

</style>
