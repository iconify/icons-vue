<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2hthea1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-data-outline-sharp" /></template>
<style>
.i2hthea1k {
  fill: currentColor;
  d: path("M14.049 21.951q-.433-.434-.433-1.066q0-.499.284-.881q.285-.383.716-.543v-6.178q-.431-.16-.716-.53t-.285-.868q0-.633.434-1.067t1.067-.434t1.066.434t.434 1.066q0 .499-.285.869t-.715.53v3.702L20 15.525v-2.242q-.43-.16-.715-.53T19 11.885q0-.633.434-1.067q.433-.433 1.066-.433t1.066.433q.434.434.434 1.067q0 .498-.285.868q-.284.37-.715.53v2.956l-5.384 1.788v1.435q.43.16.715.542t.285.88q0 .633-.434 1.067t-1.066.434t-1.067-.434M4 19V6zm-1 0V5h6.596l2 2H21v1h-9.806l-2-2H4v12h7.23v1z");
}

</style>
