<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6d7zcb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:azm-sharp" /></template>
<style>
.m6d7zcb1g {
  fill: currentColor;
  d: path("m16 17l4-4V4h-9L7 8h9zm-6 6l4-4v-9H5l-4 4h9z");
}

</style>
