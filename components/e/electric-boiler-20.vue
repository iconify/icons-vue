<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xlg1icbmr.css';
import '../../css/r/res8m0bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xlg1icbmr"/><path class="res8m0bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:electric-boiler-20" /></template>
