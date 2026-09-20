<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1lxv29ft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-arrow-outline" /></template>
<style>
.v1lxv29ft {
  fill: currentColor;
  d: path("M12.192 16.827V12.5H3.077v-1h9.115V7.173L19.788 12zm1-1.823L17.91 12l-4.718-3.004zm0-3.004");
}

</style>
