<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueoq-jg_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-end-arrow-sharp" /></template>
<style>
.ueoq-jg_k {
  fill: currentColor;
  d: path("M12.192 16.827V12.5H3.077v-1h9.115V7.173L19.788 12z");
}

</style>
