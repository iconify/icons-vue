<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af8j7_b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-open-sharp" /></template>
<style>
.af8j7_b1l {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2h9.231v1H4v9.962l2.266-7.577h16.6L20.288 19z");
}

</style>
