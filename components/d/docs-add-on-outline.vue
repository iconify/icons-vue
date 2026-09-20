<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_8pk5syo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:docs-add-on-outline" /></template>
<style>
.p_8pk5syo {
  fill: currentColor;
  d: path("M16 20.975v-3h-3v-2h3v-3h2v3h3v2h-3v3zM4 18v-2h7.075q-.075.525-.062 1t.087 1zm0-4v-2h9.65q-.575.4-1.037.9T11.8 14zm0-4V8h15v2zm0-4V4h15v2z");
}

</style>
