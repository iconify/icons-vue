<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9titsq5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:integration-instructions-sharp" /></template>
<style>
.r9titsq5j {
  fill: currentColor;
  d: path("m9.6 14.87l.708-.72L8.158 12l2.15-2.15l-.708-.72L6.73 12zm4.8 0L17.27 12L14.4 9.13l-.708.72l2.15 2.15l-2.15 2.15zM4 20V4h6.316q-.137-.766.366-1.383Q11.184 2 12 2q.835 0 1.338.617T13.685 4H20v16zm8.538-15.77q.212-.213.212-.538t-.213-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212");
}

</style>
