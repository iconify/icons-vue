<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu6v8b5xb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:elevator-rounded" /></template>
<style>
.yu6v8b5xb {
  fill: currentColor;
  d: path("M7.885 13.692v3q0 .349.23.578q.23.23.577.23h.385q.348 0 .578-.23t.23-.578v-3h.192q.314-.063.56-.264t.247-.543v-1.77q0-.632-.433-1.066q-.434-.433-1.067-.433h-1q-.632 0-1.066.433q-.434.434-.434 1.067v1.769q0 .342.248.543q.247.2.56.264zm1.753-5.304q.304-.305.304-.753t-.304-.753t-.753-.305t-.753.305t-.305.753t.305.753t.753.304t.753-.304m4.55 2.112h2.239q.165 0 .236-.128t-.004-.262l-1.138-1.82q-.073-.134-.213-.134t-.214.134l-1.138 1.82q-.073.134-.003.262t.235.128m1.333 5.21l1.138-1.82q.074-.134.003-.262t-.235-.128h-2.238q-.166 0-.236.128t.003.263l1.138 1.818q.073.135.214.135q.14 0 .213-.134M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20z");
}

</style>
