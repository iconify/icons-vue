<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugjngdcnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-alert-sharp" /></template>
<style>
.ugjngdcnz {
  fill: currentColor;
  d: path("M2 17V7h16.116v8.616q0 .388.106.734q.107.346.284.65zm18.5-3.884V7.5h1v5.616zm-.02 2.905q-.21-.21-.21-.52t.21-.521q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21");
}

</style>
