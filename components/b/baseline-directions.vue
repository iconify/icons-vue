<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfxzabbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-directions" /></template>
<style>
.tfxzabbeb {
  fill: currentColor;
  d: path("m21.41 10.59l-7.99-8c-.78-.78-2.05-.78-2.83 0l-8.01 8c-.78.78-.78 2.05 0 2.83l8.01 8c.78.78 2.05.78 2.83 0l7.99-8c.79-.79.79-2.05 0-2.83M13.5 14.5V12H10v3H8v-4c0-.55.45-1 1-1h4.5V7.5L17 11z");
}

</style>
