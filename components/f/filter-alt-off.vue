<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqox_i_ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-alt-off" /></template>
<style>
.aqox_i_ef {
  fill: currentColor;
  d: path("M14.089 11.264L7.825 5h10.156q.317 0 .467.28t-.052.55zm5.744 9.99L13 14.42v3.81q0 .328-.22.549t-.55.22h-.46q-.33 0-.55-.22t-.22-.55V12.42L2.746 4.167l.708-.713l17.092 17.092z");
}

</style>
