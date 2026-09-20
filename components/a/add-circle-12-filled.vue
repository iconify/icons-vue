<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="enpuwjrrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-circle-12-filled" /></template>
<style>
.enpuwjrrv {
  fill: currentColor;
  d: path("M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6m5-2.5a.417.417 0 0 0-.417.417v1.666H3.917a.417.417 0 0 0 0 .834h1.666v1.666a.417.417 0 0 0 .834 0V6.417h1.666a.417.417 0 0 0 0-.834H6.417V3.917A.417.417 0 0 0 6 3.5");
}

</style>
