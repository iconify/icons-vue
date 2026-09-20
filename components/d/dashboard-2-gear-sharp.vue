<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyy8etxkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dashboard-2-gear-sharp" /></template>
<style>
.uyy8etxkp {
  fill: currentColor;
  d: path("M11.192 10.808V5H21v5.808zM3 19v-5.808h8.808V19zm0-8.192V5h5.808v5.808zm13.73 10l-.107-.885q-.473-.106-.89-.32q-.416-.215-.748-.588l-.835.335l-.538-.815l.688-.577q-.165-.517-.165-1.035t.165-1.034l-.688-.577l.538-.816l.835.335q.313-.373.739-.588t.899-.32l.108-.884h1l.107.884q.473.106.9.32t.739.588l.835-.335l.538.816l-.688.577q.165.517.165 1.034q0 .518-.165 1.035l.688.577l-.538.815l-.835-.334q-.333.373-.749.587t-.89.32l-.107.885zm2.029-2.357q.625-.626.625-1.528t-.625-1.528t-1.528-.626t-1.528.626t-.626 1.528t.626 1.528t1.528.626t1.528-.626");
}

</style>
