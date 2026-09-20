<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehrkbd6tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ehrkbd6tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-curve-stepped" /></template>
