<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulq1iib-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ulq1iib-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:4k" /></template>
