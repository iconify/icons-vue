<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8vvl1d0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:feed-home" /></template>
<style>
.n8vvl1d0y {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.033 8.623l6.875-5.428q2.092-1.652 4.184 0l6.875 5.428q1.283 1.014 1.283 2.649v7.603q0 3.375-3.375 3.375H5.125q-3.375 0-3.375-3.375v-7.603q0-1.635 1.283-2.649M15.5 9h-7q-2.25 0-2.25 2.25T8.5 13.5h7q2.25 0 2.25-2.25T15.5 9m-7 5.75q-2.25 0-2.25 2.25t2.25 2.25h7q2.25 0 2.25-2.25t-2.25-2.25z");
}

</style>
