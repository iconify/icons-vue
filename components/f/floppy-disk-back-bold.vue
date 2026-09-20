<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="f4b8lbbtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:floppy-disk-back-bold" /></template>
<style>
.f4b8lbbtu {
  fill: currentColor;
  d: path("M208 28H83.31a19.86 19.86 0 0 0-14.14 5.86L33.86 69.17A19.86 19.86 0 0 0 28 83.31V208a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20M92 52h72v20H92Zm112 152H52V85l16-16v7a20 20 0 0 0 20 20h80a20 20 0 0 0 20-20V52h16Zm-76-96a42 42 0 1 0 42 42a42 42 0 0 0-42-42m0 60a18 18 0 1 1 18-18a18 18 0 0 1-18 18");
}

</style>
