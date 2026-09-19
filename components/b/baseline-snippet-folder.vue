<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_0e7f7ku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-snippet-folder" /></template>
<style>
.r_0e7f7ku {
  fill: currentColor;
  d: path("m15.88 10.5l1.62 1.62v3.38h-3v-5zM22 8v10c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2l.01-12c0-1.1.89-2 1.99-2h6l2 2h8c1.1 0 2 .9 2 2m-3 3.5L16.5 9H13v8h6z");
}

</style>
