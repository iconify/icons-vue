<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jf3lhv1er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clover-20-filled" /></template>
<style>
.jf3lhv1er {
  fill: currentColor;
  d: path("M5.5 2a3.5 3.5 0 1 0 0 7h3a.5.5 0 0 0 .5-.5v-3A3.5 3.5 0 0 0 5.5 2m0 15a3.5 3.5 0 1 1 0-7h3a.5.5 0 0 1 .5.5v3A3.5 3.5 0 0 1 5.5 17m8-15a3.5 3.5 0 1 1 0 7h-3a.5.5 0 0 1-.5-.5v-3A3.5 3.5 0 0 1 13.5 2m0 15a3.5 3.5 0 1 0 0-7h-3a.5.5 0 0 0-.5.5v3a3.5 3.5 0 0 0 3.5 3.5");
}

</style>
