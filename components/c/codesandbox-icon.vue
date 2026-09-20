<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="eg-qwiuph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codesandbox-icon" /></template>
<style>
.eg-qwiuph {
  d: path("M256 0v256H0V0zm-26.182 26.182H26.182v203.636h203.636z");
}

</style>
