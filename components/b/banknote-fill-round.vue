<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmg9ivb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:banknote-fill-round" /></template>
<style>
.pmg9ivb1v {
  fill: currentColor;
  d: path("M7 5h10a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 19H7a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5m2.236 5.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M7 11a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm10.01 0H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
