<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofln4dlhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-diamond-outline-rounded" /></template>
<style>
.ofln4dlhm {
  fill: currentColor;
  d: path("M15 16.175L19.175 12L15 7.825L10.825 12zm-.7 2.125L9 13H3q-.425 0-.712-.288T2 12t.288-.712T3 11h6l5.3-5.3q.3-.3.7-.3t.7.3l5.6 5.6q.3.3.3.7t-.3.7l-5.6 5.6q-.3.3-.7.3t-.7-.3M15 12");
}

</style>
