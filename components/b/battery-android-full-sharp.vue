<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ynxbl1b6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-full-sharp" /></template>
<style>
.ynxbl1b6d {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm18.885-2.884V9.904H22v4.212z");
}

</style>
