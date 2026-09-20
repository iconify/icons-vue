<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0mddpnpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:desktop-landscape-sharp" /></template>
<style>
.f0mddpnpo {
  fill: currentColor;
  d: path("M6.385 15.616h8.461v-4.462H6.385zm10.346-2.847h.884V8.385H9v.884h7.73zM3 19V5h18v14z");
}

</style>
