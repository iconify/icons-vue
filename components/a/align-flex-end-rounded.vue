<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob5jijb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-flex-end-rounded" /></template>
<style>
.ob5jijb4k {
  fill: currentColor;
  d: path("M3.5 21q-.213 0-.356-.144T3 20.499t.144-.356T3.5 20h17q.213 0 .356.144t.144.357t-.144.356T20.5 21zm8.308-4q-.343 0-.576-.232T11 16.192V4.808q0-.343.232-.576T11.808 4h.384q.344 0 .576.232t.232.576v11.384q0 .344-.232.576t-.576.232z");
}

</style>
