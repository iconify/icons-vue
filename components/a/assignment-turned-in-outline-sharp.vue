<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyxdzl2kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assignment-turned-in-outline-sharp" /></template>
<style>
.pyxdzl2kp {
  fill: currentColor;
  d: path("M10.562 15.396L16.958 9l-.708-.708l-5.688 5.689l-2.85-2.85l-.708.708zM4 20V4h6.316q-.137-.766.366-1.383Q11.184 2 12 2q.835 0 1.338.617T13.685 4H20v16zm1-1h14V5H5zm7.538-14.77q.212-.213.212-.538t-.212-.537T12 2.942t-.537.213t-.213.537t.213.538t.537.212t.538-.212M5 19V5z");
}

</style>
