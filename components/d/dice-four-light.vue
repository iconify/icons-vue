<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u5gdv6-ye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dice-four-light" /></template>
<style>
.u5gdv6-ye {
  fill: currentColor;
  d: path("M192 34H64a30 30 0 0 0-30 30v128a30 30 0 0 0 30 30h128a30 30 0 0 0 30-30V64a30 30 0 0 0-30-30m18 158a18 18 0 0 1-18 18H64a18 18 0 0 1-18-18V64a18 18 0 0 1 18-18h128a18 18 0 0 1 18 18Zm-100-92a10 10 0 1 1-10-10a10 10 0 0 1 10 10m56 0a10 10 0 1 1-10-10a10 10 0 0 1 10 10m-56 56a10 10 0 1 1-10-10a10 10 0 0 1 10 10m56 0a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
