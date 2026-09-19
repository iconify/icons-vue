<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdri3bpee.css';
import '../../css/m/mf-tslbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pdri3bpee"/><path class="mf-tslbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:carbon-for-ibm-product" /></template>
