<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vev2lrbbg"/><path class="ncbs0qb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:cloud" /></template>
<style>
.ncbs0qb0n {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M31 22c-.467 0-.91.085-1.339.204c.216-.526.339-1.1.339-1.704a4.5 4.5 0 0 0-4.5-4.5a4.46 4.46 0 0 0-2.701.921A6.5 6.5 0 0 0 16.5 12a6.5 6.5 0 0 0-6.131 4.357A8 8 0 1 0 8 32h23c2.762 0 5-2.238 5-5s-2.238-5-5-5");
}

.vev2lrbbg {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M27 8a7 7 0 0 0-2.015.298c.005-.1.015-.197.015-.298a5.998 5.998 0 0 0-11.785-1.573A6 6 0 0 0 11 6a6 6 0 1 0 0 12a6 6 0 0 0 5.785-4.428A6 6 0 0 0 19 14c.375 0 .74-.039 1.096-.104c-.058.36-.096.727-.096 1.104c0 3.865 3.135 7 7 7s7-3.135 7-7a7 7 0 0 0-7-7");
}

</style>
