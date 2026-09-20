<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nag3gw0qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-add-12-filled" /></template>
<style>
.nag3gw0qu {
  fill: currentColor;
  d: path("M12 3.5a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m-3-2a.5.5 0 0 0-1 0V3H6.5a.5.5 0 0 0 0 1H8v1.5a.5.5 0 0 0 1 0V4h1.5a.5.5 0 0 0 0-1H9zM8.5 8a4.5 4.5 0 0 0 2.484-.747A2 2 0 0 1 9 9H6.651l-2.874 1.916A.5.5 0 0 1 3 10.5V9a2 2 0 0 1-2-2V3a2 2 0 0 1 2-2h1.758A4.5 4.5 0 0 0 8.5 8");
}

</style>
