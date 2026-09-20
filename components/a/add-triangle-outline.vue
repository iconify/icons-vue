<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjvux3aof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-triangle-outline" /></template>
<style>
.bjvux3aof {
  fill: currentColor;
  d: path("M2.02 19L12 2l10 17zm1.724-1h16.531L12 4zm7.756-2.404h1v-1.942h1.98v-1H12.5V10.73h-1v1.923H9.539v1H11.5zm.5-2.442");
}

</style>
