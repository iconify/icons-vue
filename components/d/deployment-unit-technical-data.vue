<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc4wb_bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lc4wb_bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:deployment-unit-technical-data" /></template>
