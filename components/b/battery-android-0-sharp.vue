<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2ijr659r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-0-sharp" /></template>
<style>
.q2ijr659r {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm1-1h15.885V8H3zm17.885-1.884V9.904H22v4.212zM3 16V8h15.885v8z");
}

</style>
