<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fzub5_zdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-data-bar-20-filled" /></template>
<style>
.fzub5_zdq {
  fill: currentColor;
  d: path("M12 14a1 1 0 0 1 1 1v3a1 1 0 1 1-2 0v-3a1 1 0 0 1 1-1m3-4a1 1 0 0 1 1 1v7a1 1 0 1 1-2 0v-7a1 1 0 0 1 1-1m3 2a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0v-5a1 1 0 0 1 1-1m-2.5-7A2.5 2.5 0 0 1 18 7.5V11c-.365 0-.706.1-1 .27V11a2 2 0 1 0-4 0v2.27A2 2 0 0 0 10 15v2H4.5A2.5 2.5 0 0 1 2 14.5V8h5.086a1.5 1.5 0 0 0 1.06-.44L10.707 5zM6.982 3c.464 0 .91.185 1.238.513l1.28 1.28l-2.06 2.06A.5.5 0 0 1 7.085 7H2V5.5A2.5 2.5 0 0 1 4.5 3z");
}

</style>
