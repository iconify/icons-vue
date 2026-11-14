<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5vsuac0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hydrogen-fuel-cell" /></template>
<style>
.r5vsuac0e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 4.268q2.165.161 3.743 1.739q1.757 1.758 1.757 4.243v5.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-5.5q-2.485 0-4.243-1.757Q3.25 18.235 3.25 15.75v-5.5q0-2.485 1.757-4.243Q6.585 4.429 8.75 4.268V3q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014h5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146zm-5-.018h3.5v-.5h-3.5zm1.186 3.256Q7.75 11.718 7.75 14.5q0 1.76 1.245 3.005T12 18.75t3.005-1.245T16.25 14.5q0-2.782-3.686-6.994q-.098-.112-.232-.178q-.133-.066-.282-.076t-.29.038q-.142.047-.254.146q-.038.032-.07.07");
}

</style>
