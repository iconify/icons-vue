<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhxkr0nwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:folder-data-sharp" /></template>
<style>
.hhxkr0nwo {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v1h-5.884q-1.612 0-2.749 1.137t-1.136 2.747q0 .756.262 1.431t.738 1.181v3.777q-.152.177-.268.349T11.76 19zm11.049 2.951q-.433-.434-.433-1.066q0-.499.284-.881q.284-.383.715-.543v-6.178q-.43-.16-.715-.53t-.285-.868q0-.633.434-1.067t1.067-.434t1.066.434t.434 1.066q0 .499-.285.869t-.715.53v3.702L20 15.525v-2.242q-.43-.16-.715-.53T19 11.885q0-.633.434-1.067q.433-.433 1.066-.433t1.066.433q.434.434.434 1.067q0 .498-.285.868q-.284.37-.715.53v2.956l-5.384 1.788v1.435q.43.16.715.542t.285.88q0 .633-.434 1.067t-1.066.434t-1.067-.434");
}

</style>
