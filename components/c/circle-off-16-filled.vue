<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9dikmbyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-16-filled" /></template>
<style>
.y9dikmbyg {
  fill: currentColor;
  d: path("M1.146 1.146a.5.5 0 0 1 .708 0l13 13a.5.5 0 1 1-.707.707l-1.565-1.564A7 7 0 0 1 2.71 3.417L1.146 1.854a.5.5 0 0 1 0-.708M8 1a7 7 0 0 1 5.895 10.773l-9.67-9.669A6.97 6.97 0 0 1 8 1");
}

</style>
