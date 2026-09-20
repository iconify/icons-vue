<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl_lfobic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:co-present-sharp" /></template>
<style>
.wl_lfobic {
  fill: currentColor;
  d: path("M21 21V5H3v8H1V3h22v18zM6.175 12.825Q5 11.65 5 10t1.175-2.825T9 6t2.825 1.175T13 10t-1.175 2.825T9 14t-2.825-1.175M1 22v-2.8q0-.85.438-1.562T2.6 16.55q1.55-.775 3.15-1.162T9 15t3.25.388t3.15 1.162q.725.375 1.163 1.088T17 19.2V22z");
}

</style>
