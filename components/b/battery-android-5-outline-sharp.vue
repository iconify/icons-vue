<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgcl4nbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-5-outline-sharp" /></template>
<style>
.hgcl4nbkr {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm12-1h4.885V8H14zm6.885-1.884V9.904H22v4.212z");
}

</style>
