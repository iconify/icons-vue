<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="rr6j3fjer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bounce-28-filled" /></template>
<style>
.rr6j3fjer {
  fill: currentColor;
  d: path("M2 8a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2H5.489l9.514 9.118l9.308-8.843a1 1 0 0 1 1.378 1.45l-10 9.5a1 1 0 0 1-1.38-.003L4 10.343V16a1 1 0 1 1-2 0z");
}

</style>
