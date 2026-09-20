<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sog85lbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comment-sharp" /></template>
<style>
.sog85lbkv {
  fill: currentColor;
  d: path("M6.5 13.5h11v-1h-11zm0-3h11v-1h-11zm0-3h11v-1h-11zM3 17V3h18v17.077L17.923 17z");
}

</style>
