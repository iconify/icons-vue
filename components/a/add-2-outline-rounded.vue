<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wk85i365s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-2-outline-rounded" /></template>
<style>
.wk85i365s {
  fill: currentColor;
  d: path("M11.643 19.856q-.143-.143-.143-.356v-7h-7q-.213 0-.356-.144T4 11.999t.144-.356t.356-.143h7v-7q0-.213.144-.356T12.001 4t.356.144t.143.356v7h7q.213 0 .356.144t.144.357t-.144.356t-.356.143h-7v7q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
