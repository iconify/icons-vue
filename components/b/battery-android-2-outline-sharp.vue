<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvl66eajx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-2-outline-sharp" /></template>
<style>
.gvl66eajx {
  fill: currentColor;
  d: path("M2 17V7h17.885v10zm6-1h10.885V8H8zm12.885-1.884V9.904H22v4.212z");
}

</style>
