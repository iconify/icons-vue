<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyaj6-bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-chair-alt" /></template>
<style>
.pyaj6-bqu {
  fill: currentColor;
  d: path("M17 10c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2H7c-1.1 0-2 .9-2 2v3c0 1.1.9 2 2 2h1v2H7c-1.1 0-2 .9-2 2v7h2v-3h10v3h2v-7c0-1.1-.9-2-2-2h-1v-2zM7 8V5h10v3zm10 8H7v-2h10zm-3-4h-4v-2h4z");
}

</style>
