<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_v_tobwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:collections-bookmark-outline-sharp" /></template>
<style>
.r_v_tobwx {
  fill: currentColor;
  d: path("M8 16h12V4h-2v7l-2.5-1.5L13 11V4H8zm-2 2V2h16v16zm-4 4V6h2v14h14v2zM8 4v12zm5 7l2.5-1.5L18 11l-2.5-1.5z");
}

</style>
