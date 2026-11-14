<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eog54bbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:art-tube-carrier" /></template>
<style>
.eog54bbtr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.499 9.75H5.5q-1.75 0-1.75 3.75t1.75 3.75h10.454q-.704-1.306-.704-3.75t.704-3.75zm1.451-1.5h6.1q-1.585-2-3.05-2t-3.05 2m7.954 0H18.5q3.25 0 3.25 5.25t-3.25 5.25h-13q-3.25 0-3.25-5.25T5.5 8.25h1.596Q9.462 4.75 12 4.75t4.904 3.5m1.596 1.5q-1.75 0-1.75 3.75t1.75 3.75t1.75-3.75t-1.75-3.75");
}

</style>
