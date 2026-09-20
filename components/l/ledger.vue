<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kksubrb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ledger" /></template>
<style>
.kksubrb8j {
  d: path("M3 15.5v4.6h6.77v-1.02H3.987V15.5zm17.014 0v3.58h-5.785v1.02H21v-4.6zM9.78 8.5v7h4.45v-.92h-3.463V8.5zM3 3.9v4.6h.986V4.92h5.785V3.9zm11.23 0v1.02h5.784V8.5H21V3.9z");
}

</style>
