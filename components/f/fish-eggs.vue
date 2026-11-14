<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df2618__q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fish-eggs" /></template>
<style>
.df2618__q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.25 9.5q0-3.75 3.75-3.75q2.073 0 3 1.146q.927-1.146 3-1.146q3.75 0 3.75 3.75q0 .86-.197 1.522q3.197.266 3.197 3.728q0 3.75-3.75 3.75q-2.073 0-3-1.146q-.927 1.146-3 1.146t-3-1.146Q8.073 18.5 6 18.5q-3.75 0-3.75-3.75q0-3.462 3.197-3.728Q5.25 10.36 5.25 9.5");
}

</style>
