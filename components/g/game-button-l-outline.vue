<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvh67kl2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-l-outline" /></template>
<style>
.uvh67kl2j {
  fill: currentColor;
  d: path("M3 19V8.27q0-1.357.977-2.323t2.35-.966h11.346q1.373 0 2.35.966T21 8.269V19zm1-1h16V8.27q0-.96-.683-1.625q-.684-.664-1.644-.664H6.327q-.96 0-1.643.664Q4 7.31 4 8.27zm0 0h16zm6.864-2.879h3.773v-.838h-2.918v-5.38h-.855z");
}

</style>
