<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruaou0bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-end-diamond-rounded" /></template>
<style>
.ruaou0bvo {
  fill: currentColor;
  d: path("M14.3 18.3L9 13H3q-.425 0-.712-.288T2 12t.288-.712T3 11h6l5.3-5.3q.3-.3.7-.3t.7.3l5.6 5.6q.3.3.3.7t-.3.7l-5.6 5.6q-.3.3-.7.3t-.7-.3");
}

</style>
