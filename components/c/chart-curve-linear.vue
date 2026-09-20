<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvmh88bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fvmh88bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:chart-curve-linear" /></template>
