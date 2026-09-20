<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oeahjthtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:asterisk-bold" /></template>
<style>
.oeahjthtk {
  fill: currentColor;
  d: path("M218.29 182.17a12 12 0 0 1-16.47 4.12L140 149.19V216a12 12 0 0 1-24 0v-66.81l-61.82 37.1a12 12 0 1 1-12.35-20.58L104.68 128L41.83 90.29a12 12 0 1 1 12.35-20.58l61.82 37.1V40a12 12 0 0 1 24 0v66.81l61.82-37.1a12 12 0 1 1 12.35 20.58L151.32 128l62.85 37.71a12 12 0 0 1 4.12 16.46");
}

</style>
