<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbl8tmbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:halal-mark" /></template>
<style>
.sbl8tmbye {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M15.2 7.4q.07.052.126.119t.095.146t.059.163t.02.172q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-3.25 0-3.25 3.25t3.25 3.25q.087 0 .172.02t.163.059q.079.039.146.095t.119.126q.044.059.076.126q.032.066.051.138q.018.071.022.145t-.007.147t-.034.143q-.025.07-.063.133q-.037.064-.087.119t-.108.099q-1.779 1.334-3.993 1.124t-3.711-1.855T6 12t1.496-3.869t3.711-1.855T15.2 7.4");
}

</style>
