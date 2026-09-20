<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nprbqum_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:dice-four-thin" /></template>
<style>
.nprbqum_n {
  fill: currentColor;
  d: path("M192 36H64a28 28 0 0 0-28 28v128a28 28 0 0 0 28 28h128a28 28 0 0 0 28-28V64a28 28 0 0 0-28-28m20 156a20 20 0 0 1-20 20H64a20 20 0 0 1-20-20V64a20 20 0 0 1 20-20h128a20 20 0 0 1 20 20Zm-104-92a8 8 0 1 1-8-8a8 8 0 0 1 8 8m56 0a8 8 0 1 1-8-8a8 8 0 0 1 8 8m-56 56a8 8 0 1 1-8-8a8 8 0 0 1 8 8m56 0a8 8 0 1 1-8-8a8 8 0 0 1 8 8");
}

</style>
