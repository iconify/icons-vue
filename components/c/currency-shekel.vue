<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke6-nwbts.css';
import '../../css/o/od4sw7bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ke6-nwbts"/><path class="od4sw7bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-shekel" /></template>
