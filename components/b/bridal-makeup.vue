<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8l_i4lnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bridal-makeup" /></template>
<style>
.w8l_i4lnq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 18.875v-4.25q0-2.25-1.5-3V3q0-.236-.136-.43q-.085-.122-.211-.202t-.273-.107t-.292.007q-.146.032-.268.118l-5 3.5q-.074.051-.134.119q-.059.068-.101.149t-.064.168q-.021.088-.021.178v5.125q-1.5.75-1.5 3v4.25q0 3.375 3.375 3.375h2.75q3.375 0 3.375-3.375M7.625 11.25q-.193 0-.375.011V6.89l3.5-2.45v6.821q-.182-.011-.375-.011zm9.482 3.333l.113-.113q1.28-1.28 2.56 0l.113.113q.498.499.429 1.199q-.036.36-.208.638q.364.212.684.532q.952.952.952 2.298t-.952 2.298t-2.298.952q-3.25 0-3.25-3.25q0-2.259 1.571-2.948q-.114-.234-.143-.52q-.069-.7.428-1.199zm1.716 1.05l-.103-.103q-.22-.219-.44 0l-.103.103q.323.208.646 0M18.5 21q-1.75 0-1.75-1.75t1.75-1.75q.725 0 1.237.513q.513.512.513 1.237t-.513 1.237Q19.225 21 18.5 21");
}

</style>
