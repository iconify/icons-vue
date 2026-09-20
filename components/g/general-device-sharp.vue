<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmyxx1_md"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:general-device-sharp" /></template>
<style>
.hmyxx1_md {
  fill: currentColor;
  d: path("M8.77 17V4h6.46v13zm0 2.385v-1h6.46v1z");
}

</style>
