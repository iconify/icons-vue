<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqduyhbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-view-headline" /></template>
<style>
.sqduyhbgk {
  fill: currentColor;
  d: path("M4 15h16v-2H4zm0 4h16v-2H4zm0-8h16V9H4zm0-6v2h16V5z");
}

</style>
