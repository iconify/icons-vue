<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9b2q0b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fishing-hook" /></template>
<style>
.y9b2q0b8i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 4q0-2.25 2.25-2.25T18.25 4q0 1.837-1.5 2.174V15q0 2.175-1.538 3.712q-1.537 1.538-3.712 1.538t-3.712-1.538Q6.25 17.175 6.25 15v-2.5q0-.138.049-.267q.049-.128.14-.231q.015-.017.031-.032q.097-.098.223-.154q.125-.057.263-.065h.002L7 11.75q.138 0 .267.049q.128.049.231.14l2.25 2q.055.05.1.108q.045.059.077.126q.032.066.051.138q.018.071.023.145q.004.074-.006.147t-.034.143t-.062.133t-.086.119q-.05.055-.108.1q-.059.045-.126.077q-.066.032-.138.051q-.071.018-.145.023q-.074.004-.147-.006t-.143-.034t-.133-.062t-.119-.086L7.75 14.17V15q0 3.75 3.75 3.75T15.25 15V6.174q-1.5-.337-1.5-2.174");
}

</style>
