<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v929_cbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:item-compare-48-regular" /></template>
<style>
.v929_cbpf {
  fill: currentColor;
  d: path("M24 5c.69 0 1.25.56 1.25 1.25v35.5l-.007.128a1.25 1.25 0 0 1-2.486 0l-.007-.128V6.25c0-.69.56-1.25 1.25-1.25m-9.25 11A4.25 4.25 0 0 1 19 20.25v7.5A4.25 4.25 0 0 1 14.75 32h-7.5A4.25 4.25 0 0 1 3 27.75v-7.5A4.25 4.25 0 0 1 7.25 16zm26 0A4.25 4.25 0 0 1 45 20.25v7.5A4.25 4.25 0 0 1 40.75 32h-7.5A4.25 4.25 0 0 1 29 27.75v-7.5A4.25 4.25 0 0 1 33.25 16zm-33.5 2.5a1.75 1.75 0 0 0-1.75 1.75v7.5c0 .966.784 1.75 1.75 1.75h7.5a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75zm26 0a1.75 1.75 0 0 0-1.75 1.75v7.5c0 .966.783 1.75 1.75 1.75h7.5a1.75 1.75 0 0 0 1.75-1.75v-7.5a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
