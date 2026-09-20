<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kne7fxbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-header-20-filled" /></template>
<style>
.kne7fxbbu {
  fill: currentColor;
  d: path("M16 16h-5.5V8H18v6a2 2 0 0 1-2 2m2-9V6a2 2 0 0 0-2-2h-5.5v3zM9.5 7V4H4a2 2 0 0 0-2 2v1zM2 8v6a2 2 0 0 0 2 2h5.5V8z");
}

</style>
