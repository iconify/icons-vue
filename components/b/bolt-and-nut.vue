<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="otx9xqb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bolt-and-nut" /></template>
<style>
.otx9xqb-u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 1.75h4.5q1.036 0 1.768.732t.732 1.768v.5q0 1.036-.732 1.768q-.549.548-1.268.686V19.5q0 2.75-2.75 2.75T4.25 19.5V7.222q-2-.236-2-2.472v-.5q0-2.5 2.5-2.5m1 5.5v2.289l2.5-.625V7.25zm12.375 2.033l2.397 1.384q1.125.65 1.125 1.949v2.768q0 1.299-1.125 1.949l-2.397 1.384q-1.125.649-2.25 0l-2.397-1.384q-1.125-.65-1.125-1.949v-2.768q0-1.299 1.125-1.949l2.397-1.384q1.125-.649 2.25 0M5.75 12.539l2.5-.625v-1.453l-2.5.625zM14.5 14q0 2.5 2.5 2.5t2.5-2.5t-2.5-2.5t-2.5 2.5m-8.75.086v1.453l2.5-.625v-1.453zm0 5.414q0 1.25 1.25 1.25t1.25-1.25v-3.039l-2.5.625z");
}

</style>
