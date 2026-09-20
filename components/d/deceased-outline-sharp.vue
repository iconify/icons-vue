<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvsgoxv_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:deceased-outline-sharp" /></template>
<style>
.gvsgoxv_a {
  fill: currentColor;
  d: path("M11.266 19.808q-.225-.655-.575-1.209t-.825-1.032t-1.025-.832t-1.2-.577q.05.725.35 1.35t.8 1.125t1.125.803t1.35.372m1.45 0q.725-.056 1.355-.356t1.134-.8t.805-1.135t.356-1.36q-.646.226-1.204.576t-1.03.825t-.83 1.037t-.586 1.213m1.984-9.339q1.108-1.107 1.108-2.7V5.992l-1.75 1.475L12 4.742L9.942 7.467l-1.75-1.475V7.77q0 1.593 1.108 2.7t2.7 1.108t2.7-1.108m-3.084 10.339q-2.084 0-3.542-1.459q-1.459-1.458-1.459-3.541v-.885q1.583.244 2.889 1.138T11.5 18.25v-5.69q-1.823-.177-3.065-1.542Q7.192 9.654 7.192 7.77V3.81l2.616 2.256L12 3.195l2.192 2.87l2.616-2.255v3.96q0 1.884-1.243 3.248q-1.242 1.365-3.065 1.541v5.672q.69-1.275 1.986-2.17q1.297-.894 2.86-1.138v.885q0 2.083-1.453 3.541q-1.452 1.459-3.528 1.459zm-2.15-2.825");
}

</style>
