<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ouxbkjcpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-flow-diagonal-up-right-32-filled" /></template>
<style>
.ouxbkjcpj {
  fill: currentColor;
  d: path("M26.707 6.707a1 1 0 0 0-1.414-1.414L11.618 18.968a5.5 5.5 0 1 0 1.414 1.414z");
}

</style>
