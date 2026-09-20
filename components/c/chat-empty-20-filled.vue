<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vx3adkb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-empty-20-filled" /></template>
<style>
.vx3adkb_r {
  fill: currentColor;
  d: path("M18 10a8 8 0 1 0-16 0l.007.346l.026.382a8 8 0 0 0 .829 2.887l.063.12l-.91 3.644l-.014.083v.082a.5.5 0 0 0 .62.441l3.645-.91l.12.064A8 8 0 0 0 18 10");
}

</style>
