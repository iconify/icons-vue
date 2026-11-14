<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8d2otb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:empty-set" /></template>
<style>
.a8d2otb_h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.979 18.615q1.379.635 3.021.635q3.003 0 5.127-2.123T19.25 12t-2.123-5.127q-.395-.394-.82-.715zm6.042-13.23Q13.642 4.75 12 4.75q-3.003 0-5.127 2.123T4.75 12t2.123 5.127q.395.394.82.715z");
}

</style>
