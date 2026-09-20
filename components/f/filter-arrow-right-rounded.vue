<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypt5_fbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-arrow-right-rounded" /></template>
<style>
.ypt5_fbal {
  fill: currentColor;
  d: path("M20.079 15.289h-4.175q-.213 0-.357-.145t-.143-.356t.143-.356t.357-.144h4.175l-1.612-1.554q-.16-.135-.16-.338t.16-.363q.147-.146.35-.146q.204 0 .364.14l2.234 2.176q.13.125.183.272q.054.146.054.314q0 .158-.053.296t-.183.265l-2.254 2.2q-.136.134-.34.14q-.203.006-.349-.14q-.16-.139-.16-.353t.16-.355zm-8.887-3.143l5.643-6.165H5.55zm-1.461-.107L4.52 6.303q-.113-.116-.163-.243t-.05-.244q0-.312.23-.574t.597-.261H17.23q.367 0 .597.261q.23.262.23.574q0 .117-.05.244t-.163.243l-5.21 5.736v6.153q0 .344-.232.576q-.233.232-.576.232h-1.288q-.344 0-.576-.232t-.232-.576z");
}

</style>
