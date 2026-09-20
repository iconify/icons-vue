<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7_s83blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:domain-verification-sharp" /></template>
<style>
.w7_s83blr {
  fill: currentColor;
  d: path("m10.95 15.82l4.958-4.959l-.72-.719l-4.238 4.239l-2.138-2.139l-.72.72zM4 8h16V6H4zM3 19V5h18v14z");
}

</style>
