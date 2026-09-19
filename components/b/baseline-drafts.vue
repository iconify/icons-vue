<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iepprebrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-drafts" /></template>
<style>
.iepprebrf {
  fill: currentColor;
  d: path("M21.99 8c0-.72-.37-1.35-.94-1.7L12 1L2.95 6.3C2.38 6.65 2 7.28 2 8v10c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2zM12 13L3.74 7.84L12 3l8.26 4.84z");
}

</style>
