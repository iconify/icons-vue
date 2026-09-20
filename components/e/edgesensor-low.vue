<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvgyxfhwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:edgesensor-low" /></template>
<style>
.nvgyxfhwm {
  fill: currentColor;
  d: path("M8.423 20q-.666 0-1.14-.475t-.475-1.14V5.615q0-.666.474-1.14T8.423 4h7.154q.666 0 1.14.475t.475 1.14v12.77q0 .666-.474 1.14T15.577 20zm4.165-11.914q.22-.222.22-.549t-.222-.547t-.549-.22t-.548.22t-.22.55t.222.547t.549.22t.548-.22M4.23 13.5v-6h1v6zm14.538 3v-6h1v6z");
}

</style>
