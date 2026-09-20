<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yiqfi0bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-ad-outline" /></template>
<style>
.yiqfi0bwq {
  fill: currentColor;
  d: path("M18.192 19.385v-3h-3v-1h3v-3h1v3h3v1h-3v3zM3.423 20q-.69 0-1.153-.462t-.462-1.153V5.615q0-.69.462-1.152T3.423 4h12.77q.69 0 1.152.463t.463 1.153V10h-1V7.385h-14v11q0 .269.173.442t.442.173h12.385v1zM2.808 6.385h14v-.77q0-.269-.174-.442Q16.462 5 16.192 5H3.423q-.27 0-.442.173q-.173.173-.173.443zm0 0V5z");
}

</style>
