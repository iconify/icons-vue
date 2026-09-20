<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko0bhzb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-4-sharp" /></template>
<style>
.ko0bhzb1j {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm10-1h6.885V8H12zm8.885-1.884V9.904H22v4.212z");
}

</style>
