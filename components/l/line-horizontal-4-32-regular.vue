<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqpw1jbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-32-regular" /></template>
<style>
.uqpw1jbmk {
  fill: currentColor;
  d: path("M29 25a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H3a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H3a1 1 0 0 1 0-2z");
}

</style>
