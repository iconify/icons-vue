<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl8-4vekl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gaze-heatmap" /></template>
<style>
.yl8-4vekl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.829 11.665Q5.536 4.25 12 4.25t10.171 7.415q.039.078.059.163t.02.172t-.02.172t-.059.163Q18.464 19.75 12 19.75T1.829 12.335q-.039-.078-.059-.163T1.75 12t.02-.172t.059-.163m6.635-3.201Q7 9.929 7 12t1.464 3.536T12 17t3.536-1.464Q17 14.071 17 12t-1.464-3.536T12 7T8.464 8.464");
}

</style>
