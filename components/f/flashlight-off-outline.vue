<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edn3xqznk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flashlight-off-outline" /></template>
<style>
.edn3xqznk {
  fill: currentColor;
  d: path("m19.589 21.523l-5.108-5.108V21h-6V10.416L2.304 4.239l.708-.708l17.284 17.284zM9.48 20h4v-4.584l-4-4zm5-7.85l-1-1v-.75l2-3v-.9H8.83l-1-1h7.65V4H7.216v.885L6.48 4.15V3h10v4.692l-2 3zm-2.633-2.633");
}

</style>
