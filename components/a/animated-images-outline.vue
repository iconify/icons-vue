<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7nzapb2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:animated-images-outline" /></template>
<style>
.s7nzapb2p {
  fill: currentColor;
  d: path("m12.5 12.75l4.789-3.25L12.5 6.25zm4.354 5.712h1.485q-.002.361-.245.617t-.61.317L6.182 20.817q-.671.087-1.2-.32q-.527-.407-.608-1.078l-1.23-9.713q-.08-.672.333-1.216t1.085-.606l.977-.073v1l-.823.068q-.27.019-.424.221t-.115.471l1.196 9.713q.039.27.23.424q.193.153.463.115zm-7.7-2q-.69 0-1.153-.463t-.462-1.153V4.616q0-.691.462-1.153T9.154 3h10.23q.691 0 1.153.463T21 4.616v10.23q0 .69-.463 1.153t-1.153.463zm0-1h10.23q.27 0 .443-.173t.173-.443V4.616q0-.27-.173-.443T19.385 4H9.154q-.27 0-.442.173q-.173.173-.173.443v10.23q0 .27.173.443t.442.173M5.45 19.9");
}

</style>
