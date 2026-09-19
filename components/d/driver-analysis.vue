<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml-w7dbdb.css';
import '../../css/i/icpdw850u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="ml-w7dbdb"/><path class="icpdw850u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:driver-analysis" /></template>
