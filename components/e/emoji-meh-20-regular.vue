<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="drhdlrl7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-meh-20-regular" /></template>
<style>
.drhdlrl7s {
  fill: currentColor;
  d: path("M7.5 9.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2m6-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-7 3.5a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zM2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8-7a7 7 0 1 0 0 14a7 7 0 0 0 0-14");
}

</style>
